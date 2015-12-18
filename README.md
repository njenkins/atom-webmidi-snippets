# Web MIDI API Snippets for Atom
A few snippets for working with the [Web MIDI API](http://www.w3.org/TR/webmidi/) within [Atom](http://atom.io)
## requestMIDIAccess
### [MIDIRA]
```js
navigator.requestMIDIAccess().then(onSuccessCallback,onErrorCallback);
```  
## MIDIOutput
### [MIDIOS]
```js
MIDIOutput.send(data, timestamp);
```
### [MIDIOC]
```js
MIDIOutput.clear();
```
## MIDIPort
### [MIDIPO]
```js
MIDIPort.open();
```
### [MIDIPC]
```js
MIDIPort.close();
```
