# Macintosh Portable SCSI Adapter
An adapter from the 34-pin SCSI in the Portable to a standard 50-pin header.

Nothing fancy. Just rewires the pins in a convenient fashion, without the need for cobbling cables together. Additionally, there's an option to provide 5V to the TERMPWR pin. This could be achieved with a power diode for "high" current applications (like a SCSI to SD adapter) or a 220/330Ω resistor for current sensing only applications (as described in one of Woz's brain storm documents - can't seem to find it back).

The board has been succesfully produced by JLCPCB and Aisler, so I suppose any manufacturer of choice will do. It probably fits an entire host of different IDC connectors, but they've been succesfully fitted with Samtec's TST-125-01-G-D and TST-117-01-G-D. The 5V-GND-GND-12V "connector" could just be a floppy or hard drive wire bundle, recovered from an old ATX power supply.

The project is in KiCad format and is free for anyone to use, either personally or commercially. There is no warranty in any way, though, and I don't accept any liability resulting from some sort of misuse.
