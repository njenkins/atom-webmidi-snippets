# Web MIDI API Snippets for Atom
A few snippets for working with the [Web MIDI API](http://www.w3.org/TR/webmidi/) within [Atom](http://atom.io)

## Installation instructions
Go to Atom > File > Settings then search for MIDI in the Packages tab. Once found, install
## Development

```js
$ cd ~/.atom/packages
$ git clone https://github.com/njenkins/atom-webmidi-snippets.git
$ cd atom-webmidi-snippets
$ apm install
$ apm link
```

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
