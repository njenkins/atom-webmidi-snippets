# Web MIDI API Snippets for [ATOM](http://atom.io)
## requestMIDIAccess
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
