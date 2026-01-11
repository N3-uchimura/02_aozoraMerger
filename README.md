<table>
	<thead>
    	<tr>
      		<th style="text-align:center">English</th>
      		<th style="text-align:center"><a href="README-ja.md">日本語</a></th>
    	</tr>
  	</thead>
</table>

## name

aozoraMerger

## Overview

This is merge which merge wavs.

## Requirement

Windows10 ~

## Setting

### From souce

1. Download zip or pull repository.
2. Execute below on cmd.
   ```
   npm install
   npm start
   ```

- node.js environment required.

### From exe

1. Download exe file from release.
2. DoubleClick on exe file and install.

## Usage

1. put some wav files into resources/file/partial
2. Press "Merge" button.
3. merged wav files are restored to resources/file/output.
resources/
　└ file/
　 　├ partial/
　　 │　 ├ target1/
　　 │　 │　　├ target1-1.wav
　　 │　 │　　└ target1-2.wav
　　 │　 └ target2/
　　 │　　　　├ target2-1.wav
　　 │　　　　└ target2-2.wav
　　 └ output/
　　　　 ├ target1.wav
　　　　 └ target2.wav

## Features

- You can change default language to English by pressing "Config" button and check off "japanese".

## Author

N3-Uchimura

## Licence

[MIT](https://mit-license.org/)
