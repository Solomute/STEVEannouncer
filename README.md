If you are here you have probably opened up one of my announce boxes and are trying to fix it.

The buttons and potentiometers are connected to the board via JST PH 2mm headers. You can buy pre-terminated PH cables from many electronics suppliers, including Amazon. JST makes many models of connector, ensure you are buying the PH.

The buttons are SPST NO. I use a Cherry MX mechanical keyboard switch, the top panel cutout is 0.55" square for a Cherry MX or compatible switch to snap into. Many other brands of mechanical keyboard switches are also designed to snap into the same cutout. Simply search the web for "mechanical keyboard switch."

The potentiometers are 10k linear. Do not use a pot with a value other than 10k. Do not use an "audio" or "log" taper pot. The longest-life pots as of the time of this writing use conductive plastic as the resistance element. Avoid carbon. The front panel cutouts for the pots are sized for a standard 6mm diameter shaft. 1/4" diameter shafts should fit too. For knob compatibility get a pot with a 6mm 18T knurled shaft. If you get some other size, or a flatted-D shaft, you're on your own for knobs.

I used a P160KN-0QD15B10K from TT Electronics, but compatibile parts are available from many manufacturers.

My recommendation is that if you are using these boxes in a production environment, you keep a few extra potentiometers and buttons around pre-wired with JSTs. This way, if a pot or button starts dying, you can swap it out in only a couple of minutes. Maybe even during a commercial break!

No audio flows through the buttons or pots. The box will pass audio with a failed switch. A failed pot will cause the headphone to mute, though in practice, the headphone circuit should keep working flawlessly with pots that are degraded well past the point where they would start sounding "scratchy" if audio were passing directly through them.

XLR Input (female) connectors are Neutrik NC3FAH2. XLR Output (male) connectors are Neutrik NC3MAH. 1/4" TRS headphone connectors are Neutrik NRJ6HF. The DC power input is Switchcraft L721RALP.

Neutrik makes many connectors which are electrically and mechanically compatible with the above, and they all should work. For an alternative to the Switchcraft part, you could use a panel-mounted barrel jack and simply run wires off it into the PCB if necessary.

I strongly recommend a *threaded* barrel jack, and power supplies with *threaded* barrel plugs. Being able to lock the power connector is the reason I used a barrel jack instead of a USB plug for DC power.

For more esoteric repairs, consult the schematics. If THAT Corp or Texas Instruments have gone out of business by the time you read this, God help you. Most other parts on the board are generic, but hi-fi audio parts and switching regulators are hard to multi-source, unfortunately.

Design files for the enclosure are also included - You might be able to get away with 3D printing it, but I recommend using SendCutSend to have it cut and bent out of sheet metal with PCB standoffs inserted. Use 6mm M3x0.5 standoffs. OSHCut is talking about adding hardware insertion to their services, so they might be an option as well by the time you read this.

Good luck!
