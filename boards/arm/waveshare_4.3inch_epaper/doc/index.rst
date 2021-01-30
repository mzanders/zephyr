.. _waveshare_4.3inch_epaper_board:

Waveshare 4.3inch  ePaper
#########################

Overview
********

The Waveshare 4.3inch ePaper is a display module equipped with STM32F103ZE MCU.


Hardware
********
Supported Features
==================

The Waveshare 4.3inch ePaper configuration supports the following hardware
features:

+-----------+------------+--------------------------------------+
| Interface | Controller |      Driver/Component                |
+===========+============+======================================+
| NVIC      | on-chip    | nested vectored interrupt controller |
+-----------+------------+--------------------------------------+
| UART      | on-chip    | serial port                          |
+-----------+------------+--------------------------------------+
| GPIO      | on-chip    | gpio                                 |
+-----------+------------+--------------------------------------+
| FLASH     | on-chip    | flash                                |
+-----------+------------+--------------------------------------+
| CAN       | on-chip    | can                                  |
+-----------+------------+--------------------------------------+

Programming and Debugging
*************************

Applications for the ``waveshare_open103z`` board configuration can be built and
flashed in the usual way.

Flashing
========

Build and flash applications as usual. Here is an example for the
:ref:`hello_world` application.

.. zephyr-app-commands::
   :zephyr-app: samples/hello_world
   :board: waveshare_open103z
   :goals: build flash

Debugging
=========

Debug applications as usual. Here is an example for the
:ref:`hello_world` application.

.. zephyr-app-commands::
   :zephyr-app: samples/hello_world
   :board: waveshare_open103z
   :maybe-skip-config:
   :goals: debug
