# The-Quantified-Self

Autoregulatve Spaces - The Quantified self is an interactive art installation by [alien productions](http://alien.mur.at).

Biometrical data (like skin resistance, pulse) of the visitors are captured on their smartphones and projected on screens and processed as an audio installtion. 

This code, written in Pure Data, is used to process the biometrical data and to transform them into MIDI signals and to create the visual representation.

On the smartphones is installed [this application](https://play.google.com/store/apps/details?id=com.GSR.gasperi&hl=en_US) by Michael Gasperi which outputs a sound signal. The frequency of the audio signal depends on the galvanic skin response of the user. My Pure Data patch analyzes the pich of this signal.
