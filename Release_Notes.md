---
pagetitle: Release Notes for LIS2MDL Component
lang: en
header-includes: <link rel="icon" type="image/x-icon" href="_htmresc/favicon.png" />
---

::: {.row}
::: {.col-sm-12 .col-lg-4}

<center>
# Release Notes for LIS2MDL Component Driver
Copyright &copy; 2021 STMicroelectronics\

[![ST logo](_htmresc/st_logo_2020.png)](https://www.st.com){.logo}
</center>

# License

This software component is licensed by ST under BSD 3-Clause license, the "License".
You may not use this component except in compliance with the License. You may obtain a copy of the License at:

[BSD 3-Clause license](https://opensource.org/licenses/BSD-3-Clause)

# Purpose

This directory contains the LIS2MDL component drivers.
:::

::: {.col-sm-12 .col-lg-8}
# Update history

::: {.collapse}
<input type="checkbox" id="collapse-section1" aria-hidden="true">
<label for="collapse-section1" aria-hidden="true">V1.0.0 / 18-June-2021</label>
<div>

## Main changes

### First release

- First official release [ref. DS v5.0]

##

</div>

<input type="checkbox" id="collapse-section2" aria-hidden="true">
<label for="collapse-section2" aria-hidden="true">V1.1.0 / 01-June-2023</label>
<div>

## Main changes

- Add __weak directive to read/write registers routines
- lis2mdl_reg.h: Extend stmdev_ctx_t structure with mdelay callback
- repo name changed adding '-pid' extension.
- lis2mdl_reg.c: Fix typos inlis2mdl_mag_user_offset_set routine

##

</div>

<input type="checkbox" id="collapse-section3" aria-hidden="true">
<label for="collapse-section3" aria-hidden="true">V1.1.1 / 09-Nov-2023</label>
<div>

## Main changes

- The sensitivity is 8 LSB/C, but on 12bit resolution data. 

##

</div>

<input type="checkbox" id="collapse-section4" aria-hidden="true">
<label for="collapse-section4" aria-hidden="true">V2.0.0 / 20-Mar-2024</label>
<div>

## Main changes

- Fixed code style (Artistic Style Version 3.4.13)
- Fix driver's typo
- Add "const" to ctx arg for all APIs
- Revert "correct API to convert LSB to Celsius"

##

</div>

<input type="checkbox" id="collapse-section5" aria-hidden="true">
<label for="collapse-section5" aria-hidden="true">V2.0.1 / 20-Jun-2024</label>
<div>

## Main changes

- updated README.md file with tag reference and mdelay description

##

</div>

<input type="checkbox" id="collapse-section6" aria-hidden="true">
<label for="collapse-section6" aria-hidden="true">V2.1.0 / 07-Jul-2025</label>
<div>

## Main changes

- Fix driver formatting options
- Added pointer to private data in stmdev_ctx_t

##

</div>

<input type="checkbox" id="collapse-section7" aria-hidden="true">
<label for="collapse-section7" aria-hidden="true">V2.2.0 / 06-Oct-2025</label>
<div>

## Main changes

- Added checks after reads to avoid write random content on pointers
- Adding CODE_OF_CONDUCT.md and SECURITY.md

##

</div>

<input type="checkbox" id="collapse-section8" aria-hidden="true">
<label for="collapse-section8" aria-hidden="true">V2.2.1 / 05-Nov-2025</label>
<div>

## Main changes

- add a check for a DS constraint

##

</div>

<input type="checkbox" id="collapse-section9" checked aria-hidden="true">
<label for="collapse-section9" aria-hidden="true">V2.3.0 / 15-Jan-2026</label>
<div>

## Main changes

- Restore reset_set/get boot_set/get APIs for consistency
- Add sw_reset and reboot procedures to align with application note, remove reset_set/get boot_set/get

##

</div>
:::


:::
:::

<footer class="sticky">
::: {.columns}
::: {.column width="95%"}
For complete documentation on LIS2MDL,
visit:
[LIS2MDL](https://www.st.com/content/st_com/en/products/mems-and-sensors/e-compasses/lis2mdl.html)
:::
::: {.column width="5%"}
<abbr title="Based on template cx566953 version 2.0">Info</abbr>
:::
:::
</footer>
