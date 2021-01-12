# ATSAMD10D-DMA-UART-hard-fault-debugging
ATSAMD10D hard faults when DMA transfer is complete before it can call DMA transfer complete callback.
This is fixed, turns out START.Atmel screwed someting up.
