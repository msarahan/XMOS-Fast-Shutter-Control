################################################################################
# Automatically-generated file. Do not edit!
################################################################################

-include ../makefile.init

RM = del /q $(subst /,\,$(1))

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir.mk
-include src/subdir.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(XC_DEPS)),)
-include $(XC_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 

# All Target
all: FBS.xe

# Tool invocations
FBS.xe: $(OBJS) $(XTA_SRCS)
	@echo 'Building target: $@'
	@echo 'Invoking: Mapper/Linker'
	xcc -target=XC-1A -Werror=timing-syntax -o FBS.xe $(OBJS) $(LIBS) $(XTA_SRCS)
	@echo 'Finished building target: $@'
	@echo ' '

# Other Targets
clean:
	-$(call RM, $(C++_DEPS)$(OBJS)$(C_DEPS)$(CC_DEPS)$(XC_DEPS)$(CPP_DEPS)$(EXECUTABLES)$(CXX_DEPS)$(C_UPPER_DEPS) FBS.xe)
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets
