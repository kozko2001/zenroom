# Zenroom - crypto language VM

[![software by Dyne.org](https://zenroom.dyne.org/img/software_by_dyne.png)](http://www.dyne.org)

Zenroom is a brand new virtual machine for fast cryptographic operations on Elliptic Curves. The Zenroom VM has no external dependencies, includes a cutting edge selection of C99 libraries and builds a small executable ready to run on: desktop, embedded, mobile, cloud and browsers (webassembly). It also compiles unikernel (without Linux).

Zencode is the name of the language executed by Zenroom: it is simple to understand and can process large data structures while operating cryptographic transformations on them. Zencode is a Domain Specific Language whose design is informed by pilot use-cases in DECODE.

## Latest stable release is 0.8.0:
<ul class="center">

<li class="fab fa-node-js"><a href="https://files.dyne.org/zenroom/releases/Zenroom-0.8.0-javascript.zip">Javscript (nodeJS and WASM)</a></li>

<li class="fab fa-linux"><a href="https://files.dyne.org/zenroom/releases/Zenroom-0.8.0-linux.zip">Linux (ARM and x86)</a></li>

<li class="fab fa-windows"><a href="https://files.dyne.org/zenroom/releases/Zenroom-0.8.0-windows.zip">Windows (EXE and DLL)</li>

<li class="fab fa-apple"><a href="https://files.dyne.org/zenroom/releases/Zenroom-0.8.0-apple.zip">Apple (OSX and iOS)</li>

<li class="far fa-file-archive"><a href="https://files.dyne.org/zenroom/releases/Zenroom-0.8.0.tar.gz">Source Code</a></li>

<li class="fab fa-github"><a href="https://github.com/decodeproject/zenroom">Git repository</a></li>

<li class="far fa-archive"><a href="https://files.dyne.org/zenroom/">Releases archive</a></li>
</ul>

## Documentation:

<ul class="center"
>
<li class="fas fa-code"><a href="https://zenroom.dyne.org/api">Zencode language API</a></li>

<li class="far fa-graduation-cap"><a href="https://zenroom.dyne.org/whitepaper">Zenroom Whitepaper</a></li>

<li class="far fa-hand-point-right"><a href="https://zenroom.dyne.org/demo">Online Demo</a></li>

<li class="far fa-cogs"><a href="https://github.com/DECODEproject/zenroom/wiki">Online Wiki</a></li>

<li class="fas fa-history"><a href="https://files.dyne.org/zenroom/ChangeLog.txt">History of changes</a></li>
</ul>


Zenroom is software in **ALPHA stage** and is part of the [DECODE project](https://decodeproject.eu) about data commons and [technological sovereignty](https://www.youtube.com/watch?v=RvBRbwBm_nQ). Our effort is that of improving people's awareness of how their data is processed by algorithms, as well facilitate the work of developers to create along [privacy by design principles](https://decodeproject.eu/publications/privacy-design-strategies-decode-architecture).

<a href="https://decodeproject.eu">
<img src="https://zenroom.dyne.org/img/decode.svg" width="54%"
	alt="DECODE project"></a>

This software aims to make it easy and less error-prone to write **portable** scripts using **end-to-end encryption** inside isolated environments that can be easily made **interoperable**. Basic crypto functions provided include primitives to manage **a/symmetric keys, key derivation, hashing and signing functionalities**.

Zenroom is software inspired by the [language-theoretical security](http://langsec.org) research, it allows to expresses cryptographic operations in a readable scripting language that has no access to the calling process, underlying operating system or filesystem.

<a href="http://langsec.org/occupy/">
<img src="https://zenroom.dyne.org/img/InputLanguages.jpg" class="pic"
	alt="No more Turing Completion!" target="_blank"></a>

Zenroom's **restricted execution environment** is a sort of [sandbox](https://en.wikipedia.org/wiki/Sandbox_%28computer_security%29) whose parser is based on LUA's [syntax-direct translation](https://en.wikipedia.org/wiki/Syntax-directed_translation) and has coarse-grained control of computations and memory. The Zenroom VM is designed to "brittle" and exit execution returning a meaningful message on any error.

Zenroom's documentation and examples are being written to encourage a [declarative](https://en.wikipedia.org/wiki/Declarative_programming) approach to scripting, providing functional tools to manipulate efficiently even complex data structures.


<a href="http://langsec.org/occupy/">
<img src="https://zenroom.dyne.org/img/FullRecognition.jpg" class="pic"
	alt="Full Recognition Before Processing!" target="_blank"></a>


The main use case for Zenroom is that of **distributed computing** of untrusted code where advanced cryptographic functions are required, for instance it can be used as a distributed ledger implementation (also known as **blockchain smart contracts**).

<img src="https://zenroom.dyne.org/img/ec_logo.png" class="pic"
	alt="Project funded by the European Commission">

This project is receiving funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement nr. 732546 (DECODE).


## Acknowledgements

Copyright (C) 2017-2018 by Dyne.org foundation, Amsterdam

Designed, written and maintained by Denis Roio <jaromil@dyne.org>

With contributions by Ivan J., Puria Nafisi Azizi, Jordi Coscolla,
Christian Espinoza, Enrico Zimuel and Daniele Lacamera.

Special thanks to Francesca Bria for leading the DECODE project and to
George Danezis, Ola Bini, Mark de Villiers, Alberto Sonnino and
Richard Stallman for their expert reviews.

This software includes software components by: R. Ierusalimschy,
W. Celes and L.H. de Figueiredo (lua), Mike Scott and Kealan McCusker
(milagro-crypto-c), Ralph Hempel (umm_malloc), Mark Pulford
(lua-cjson), Daan Sprenkels (randombytes), Luke-jr (base58), Salvatore
Sanfilippo (cmsgpack)

Lua extensions written and documented by: Roland Yonaba (moses),
Enrique García Cota (inspect), Sebastian Schoener (schema), Kyle
Conroy (finite state machine), Scott Lembcke (debugger), Gianluca
Vespignani (comparetables).

Zenroom is Licensed under the terms of the GNU Public License as
published by the Free Software Foundation; either version 3 of the
License, or (at your option) any later version.

Software contained include Lua 5.3, Copyright (C) 1994-2017 Lua.org,
PUC-Rio licensed with an MIT style license. Also included Milagro,
Copyright 2016 MIRACL UK Ltd licensed with the Apache License, Version
2.0 (the "License").

<!-- We are committed to contribute our code to communities and societies -->
<!-- adopting it as free and open source, according to the Free Software -->
<!-- Foundation guidelines and GNU artisanal traditions. Here is our -->
<!-- [Contributor License Agreement](Agreement.md). -->

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
implied.  See [the License](LICENSE.txt).
