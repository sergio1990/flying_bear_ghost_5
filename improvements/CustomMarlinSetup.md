# Custom Marlin setup

Previously, when working on the [silent drivers](SilentDrivers.md) improvement
I decided to install the [Marlin](https://marlinfw.org/) firmware. First of
all, I was looking for the quick solution, so all the motors rotate correctly
and decided to use one of the available Marlin builds. It worked well, but the
time has come to configure the Marlin based on my own needs. There are a lot of
tutorials how to configure and build the Marlin firmware, also the [official
docs](https://marlinfw.org/docs/configuration/configuration.html) are pretty
good. Here I'd simply like to share my config files without any further
explanations how to use them since as I've mentioned earlier there are a lot of
information available all over the Internet.

Under the [resources/custom_marlin](https://github.com/sergio1990/flying_bear_ghost_5/tree/main/improvements/resources/custom_marlin) folder you can find the next files:

- `Configuration.h`
- `Configuration_adv.h`
- `Robin_nano35.bin`

All of these files represents the latest Marlin configuration and the build,
which I used on my copy of the FB Ghost 5 3D printer. All of the mentioned
files will be changed over time.
