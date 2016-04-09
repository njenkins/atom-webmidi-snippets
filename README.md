# Web MIDI API Snippets for Atom

[![Build Status](https://travis-ci.org/njenkins/atom-webmidi-snippets.svg?branch=master)](https://travis-ci.org/njenkins/atom-webmidi-snippets)


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
### [midira]
```js
navigator.requestMIDIAccess().then(${1:onSuccessCallback}, ${2:onErrorCallback});
```
## MIDIOutput
### send
#### [midios]
```js
${1:MIDIOutput}.send(${2:data}, ${3:timestamp});
```
### clear
#### [midioc]
```js
${1:MIDIOutput}.clear();
```
## MIDIPort
### open
#### [midipo]
```js
${1:MIDIPort}.open();
```
### close
#### [midipc]
```js
${1:MIDIPort}.close();
```
