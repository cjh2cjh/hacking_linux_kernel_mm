# table of content
* [real address mode](#real-address-mode)
* [protected mode](#protected-mode)
* [system management mode](#system-management-mode)

## real address mode
* implements the programming environment for Intel8086
* the ability to switch to 'protected mode' and 'system management mode'

## protected mode
* provide 'virtual-8086 mode' for running software designed for 8086
* 'virtual-8086 mode' is actual a protected mode attribute that can be
enable for any task

## system management mode
* power management, system security
* when to enter system management mode(SMM)?
  * external SMM interrupt pin (SMI#) is activated or
  * SMI is received from the advanced programmable interrupt controller(APIC)
* SMM has its separate address space ( a separate physical memory space? )
