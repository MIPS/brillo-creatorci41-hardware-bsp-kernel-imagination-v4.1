dtb-$(CONFIG_MACH_PISTACHIO)	+= pistachio_bub.dtb pistachio_buranku.dtb pistachio_fpga.dtb pistachio_kennet.dtb

obj-y				+= $(patsubst %.dtb, %.dtb.o, $(dtb-y))

# Force kbuild to make empty built-in.o if necessary
obj-				+= dummy.o

always				:= $(dtb-y)
clean-files			:= *.dtb *.dtb.S
