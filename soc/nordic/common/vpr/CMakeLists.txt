# Copyright (c) 2024 Nordic Semiconductor ASA
# SPDX-License-Identifier: Apache-2.0

zephyr_include_directories(.)

<<<<<<< HEAD
zephyr_library_sources(soc_idle.c soc_irq.S soc_irq.c vector.S)
=======
zephyr_library_sources(soc_context.S soc_idle.c soc_init.c)
>>>>>>> origin/v3.6.99-ncs2-cetus-1

set(SOC_LINKER_SCRIPT ${ZEPHYR_BASE}/include/zephyr/arch/riscv/common/linker.ld CACHE INTERNAL "")
