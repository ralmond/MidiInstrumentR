# MidiInstrumentR
Wrapper for fluidSynth to serve as an orchestral instrument.

I'm looking for a way to use any generic midi controller (I'm using a Re.corder, 
but any midi keyboard should do) to play a single instrument, filling in for any missing
part in an orchestra or band.  

The system needs to do the following things:
1) Map midi chanel 1 to an aribrary instrument in the sound font.
2) Turn on/off octave shifts.
3) Turn on/off automatic transposition.
4) Pair an instrument and transposition (e.g., if playing from a Clarinet or Trumpet part in the transposed key, have the sounds come out at concert pitch.

I'm working in Rust because I hear it is fast.

