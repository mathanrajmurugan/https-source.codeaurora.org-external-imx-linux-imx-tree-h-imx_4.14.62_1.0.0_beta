# SPDX-License-Identifier: GPL-2.0

obj-$(CONFIG_ARM)   += \
	clk.o \
	clk-busy.o \
	clk-cpu.o \
	clk-fixup-div.o \
	clk-fixup-mux.o \
	clk-gate-exclusive.o \
	clk-gate2.o \
	clk-pllv1.o \
	clk-pllv2.o \
	clk-pllv3.o \
	clk-pfd.o \
	clk-composite.o \
	clk-pllv4.o \
	clk-pllv5.o \
	clk-pfdv2.o

obj-$(CONFIG_SOC_IMX1)   += clk-imx1.o
obj-$(CONFIG_SOC_IMX21)  += clk-imx21.o
obj-$(CONFIG_SOC_IMX25)  += clk-imx25.o
obj-$(CONFIG_SOC_IMX27)  += clk-imx27.o
obj-$(CONFIG_SOC_IMX31)  += clk-imx31.o
obj-$(CONFIG_SOC_IMX35)  += clk-imx35.o
obj-$(CONFIG_SOC_IMX5)   += clk-imx51-imx53.o
obj-$(CONFIG_SOC_IMX6Q)  += clk-imx6q.o
obj-$(CONFIG_SOC_IMX6SL) += clk-imx6sl.o
obj-$(CONFIG_SOC_IMX6SLL) += clk-imx6sll.o
obj-$(CONFIG_SOC_IMX6SX) += clk-imx6sx.o
obj-$(CONFIG_SOC_IMX6UL) += clk-imx6ul.o
obj-$(CONFIG_SOC_IMX7D)  += clk-imx7d.o
obj-$(CONFIG_SOC_IMX7ULP)  += clk-imx7ulp.o
obj-$(CONFIG_SOC_VF610)  += clk-vf610.o
#
# IMX Clock specific Makefile
#
obj-$(CONFIG_ARCH_FSL_IMX8QM)	+= clk.o clk-imx8qm.o clk-imx8.o clk-divider-scu.o clk-gate-scu.o clk-mux-scu.o
obj-$(CONFIG_ARCH_FSL_IMX8QXP)	+= clk.o clk-imx8qxp.o clk-imx8.o clk-divider-scu.o clk-gate-scu.o clk-mux-scu.o
obj-$(CONFIG_ARCH_FSL_IMX8MQ)	+= clk.o clk-imx8mq.o clk-frac-pll.o clk-sccg-pll.o clk-gate2.o
obj-$(CONFIG_ARCH_FSL_IMX8MM)	+= clk.o clk-imx8mm.o clk-intpll.o clk-gate2.o clk-cpu.o
