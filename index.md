---
layout: default
title: {{ site.name }}
---

---


# Table of contents

* [Abstract](#abstract)
<!-- * [Model Description](#model) -->
* [Results](#results)
  * [FMA](#FMA)
  * [MUSICNET](#MUSICNET)
  * [VCTK](#VCTK)
  * [YANG](#YANG)

---

<a name="abstract"></a>
# Abstract
<font family = "Times New Roman">We proposed a novel approach in the field of time-scale modification on the audio signals. While traditional methods use framing technique and spectral approaches use shorttime Fourier transform to get high-level units. TSM-Net, our neural-network model encodes the raw audio into a high-level latent representation called Neuralgram. Since the resulting Neuralgram is a two-dimensional image with real values, we apply some existing image resizing techniques on the Neuralgram and decode it using our neural decoder to obtain the time-scaled audio. Both the encoder and decoder is trained with GANs, which shows fair generalization ability on the unseen scaled Neuralgrams. Our method yields little artifacts and opens a new possibility in the research of modern time-scale modification.</font>

<!-- <a name="model"></a>
# Model Description -->
<a name="results"></a>
# Results

<!--<font family = "微軟正黑體" color = "#dd0000"> Original&#128511;: </font><br />-->

<a name="FMA"></a> 

## FMA
<table>
<col width="50">
<col width="50">
<col width="50">
<col width="50">
<col width="50">
<col width="50">
<col width="50">
<tr>
 <th/>
 <th>0.5x</th>
 <th>0.75</th>
 <th>1.0x</th>
 <th>1.25x</th>
 <th>1.5x</th>
 <th>1.75x</th>
 <th>2.0x</th>
</tr>

<tr>
<th> 1024 </th>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/1024/reconstruct0.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/1024/reconstruct0.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/1024/reconstruct1.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>


<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/1024/reconstruct1.25x (1).wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/1024/reconstruct1.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/1024/reconstruct1.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/1024/reconstruct2.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
</tr>

<tr>
<th> 512 </th>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/512/512reconstruct0.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/512/512reconstruct0.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>


<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/512/512reconstruct1.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/512/512reconstruct1.25x (1).wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/512/512reconstruct1.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/512/512reconstruct1.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/512/512reconstruct2.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
</tr>

<tr>
<th> 256 </th>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/256/256reconstruct0.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/256/256reconstruct0.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>


<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/256/256reconstruct1.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/256/256reconstruct1.25x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/256/256reconstruct1.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/256/256reconstruct1.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/256/256reconstruct2.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
</tr>
 
<th> librosa </th>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/librosa/fmareconstruct0.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/librosa/fmareconstruct0.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>


<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/librosa/fmareconstruct1.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/librosa/fmareconstruct1.25x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/librosa/fmareconstruct1.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/librosa/fmareconstruct1.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/FMA/librosa/fmareconstruct2.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>




</table>

<a name="musicnet"></a>
## MUSICNET
<table>
<col width="50">
<col width="50">
<col width="50">
<col width="50">
<col width="50">
<col width="50">
<col width="50">
<tr>
 <th/>
 <th>0.5x</th>
 <th>0.75</th>
 <th>1.0x</th>
 <th>1.25x</th>
 <th>1.5x</th>
 <th>1.75x</th>
 <th>2.0x</th>
</tr>

<tr>
<th> 1024 </th>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/1024/reconstruct0.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/1024/reconstruct0.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/1024/reconstruct1.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>


<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/1024/reconstruct1.25x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/1024/reconstruct1.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/1024/reconstruct1.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/1024/reconstruct2.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
</tr>

<tr>
<th> 512 </th>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/512/512reconstruct0.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/512/512reconstruct0.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>


<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/512/512reconstruct1.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/512/512reconstruct1.25x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/512/512reconstruct1.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/512/512reconstruct1.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/512/512reconstruct2.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
</tr>

<tr>
<th> 256 </th>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/256/256reconstruct0.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/256/256reconstruct0.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>


<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/256/256reconstruct1.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/256/256reconstruct1.25x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/256/256reconstruct1.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/256/256reconstruct1.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/256/256reconstruct2.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
</tr>
 
<th> librosa </th>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/librosa/musicnetreconstruct0.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/librosa/musicnetreconstruct0.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>


<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/librosa/musicnetreconstruct1.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/librosa/musicnetreconstruct1.25x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/librosa/musicnetreconstruct1.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/librosa/musicnetreconstruct1.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/musicnet/librosa/musicnetreconstruct2.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>





</table>

<a name="VCTK"></a>
## VCTK
<table>
<col width="50">
<col width="50">
<col width="50">
<col width="50">
<col width="50">
<col width="50">
<col width="50">
<tr>
 <th/>
 <th>0.5x</th>
 <th>0.75</th>
 <th>1.0x</th>
 <th>1.25x</th>
 <th>1.5x</th>
 <th>1.75x</th>
 <th>2.0x</th>
</tr>

<tr>
<th> 1024 </th>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/1024/reconstruct0.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/1024/reconstruct0.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/1024/reconstruct1.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>


<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/1024/reconstruct1.25x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/1024/reconstruct1.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/1024/reconstruct1.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/1024/reconstruct2.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
</tr>

<tr>
<th> 512 </th>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/512/512reconstruct0.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/512/512reconstruct0.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>


<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/512/512reconstruct1.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/512/512reconstruct1.25x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/512/512reconstruct1.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/512/512reconstruct1.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/512/512reconstruct2.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
</tr>

<tr>
<th> 256 </th>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/256/256reconstruct0.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/256/256reconstruct0.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>


<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/256/256reconstruct1.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/256/256reconstruct1.25x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/256/256reconstruct1.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/256/256reconstruct1.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/256/256reconstruct2.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
</tr>


<th> librosa </th>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/librosa/VCTKreconstruct0.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/librosa/VCTKreconstruct0.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>


<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/librosa/VCTKreconstruct1.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/librosa/VCTKreconstruct1.25x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/librosa/VCTKreconstruct1.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/librosa/VCTKreconstruct1.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/VCTK/librosa/VCTKreconstruct2.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>


</table>

<a name="YANG"></a>
## YANG
<table>
<col width="50">
<col width="50">
<col width="50">
<col width="50">
<col width="50">
<col width="50">
<col width="50">
<tr>
 <th/>
 <th>0.5x</th>
 <th>0.75</th>
 <th>1.0x</th>
 <th>1.25x</th>
 <th>1.5x</th>
 <th>1.75x</th>
 <th>2.0x</th>
</tr>

<tr>
<th> 1024 </th>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/1024/reconstruct0.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/1024/reconstruct0.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/1024/reconstruct1.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>


<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/1024/reconstruct1.25x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/1024/reconstruct1.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/1024/reconstruct1.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/1024/reconstruct2.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
</tr>

<tr>
<th> 512 </th>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/512/512reconstruct0.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/512/512reconstruct0.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>


<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/512/512reconstruct1.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/512/512reconstruct1.25x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/512/512reconstruct1.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/512/512reconstruct1.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/512/512reconstruct2.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
</tr>

<tr>
<th> 256 </th>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/256/256reconstruct0.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/256/256reconstruct0.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>


<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/256/256reconstruct1.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/256/256reconstruct1.25x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/256/256reconstruct1.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/256/256reconstruct1.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/256/256reconstruct2.0x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
</tr>

<th> librosa </th>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/librosa/Yreconstruct0.5.x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/librosa/Yreconstruct0.75x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>


<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/librosa/Yreconstruct1.0.x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>

<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/librosa/Yreconstruct1.25x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/librosa/Yreconstruct1.5x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/librosa/Yreconstruct1.75.x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
<td>
 <audio controls style="width: 170px;">
   <source src="assets/yang/librosa/Yreconstruct2.0.x.wav" type="audio/wav">
   Your browser does not support the audio element.
 </audio>
</td>
 

</table>
