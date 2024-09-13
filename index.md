# Single-stage TTS with Masked Audio Token Modeling and Semantic Knowledge Distillation

This is the demonstration page of the paper "Single-stage TTS with Masked Audio Token Modeling and Semantic Knowledge Distillation" with some selected samples generated with the proposed methods.

## Info

### Abstract

Audio token modeling has become a powerful framework for speech synthesis, with two-stage approaches employing semantic tokens remaining prevalent. In this paper, we aim to simplify this process by introducing a semantic knowledge distillation method that enables high- quality speech generation in a single stage. Our proposed model improves speech quality, intelligibility, and speaker similarity compared to a single- stage baseline. Although two-stage systems still lead in intelligibility, our model significantly narrows the gap while delivering comparable speech quality. These findings showcase the potential of single-stage models to achieve efficient, high-quality TTS with a more compact and streamlined architecture.

## Demos

The following examples are selected from the listening test described in the paper, which are generated from LibriSpeech test-clean subset. The models to compare include one single-stage model (NARSiS) without SKD (semantic knowledge distillation), one single-stage models with SDK, and a two-stage model.

### Text: "this evening they all said"
<html>
<table>
  <tr>
    <td>
      NARSiS<sub>base</sub>
    </td>
    <td>
      NARSiS<sub>avg</sub>
    </td>
    <td>
      NAT 2-stage
    </td>
    <td>
      Ground truth
    </td>
  </tr>
  <tr> 
    <td>
        <audio controls>
        <source src="audios/672-122797-0028.vanilla.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/672-122797-0028.avg.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/672-122797-0028.2stages.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/672-122797-0028.gt.wav">
        </audio>
    </td>
  </tr>
</table>
</html>
### Text: "the paris plant like that at the crystal palace was a temporary exhibit"
<html>
<table>
  <tr>
    <td>
      NARSiS<sub>base</sub>
    </td>
    <td>
      NARSiS<sub>avg</sub>
    </td>
    <td>
      NAT 2-stage
    </td>
    <td>
      Ground truth
    </td>
  </tr>
  <tr> 
    <td>
        <audio controls>
        <source src="audios/2300-131720-0000.vanilla.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/2300-131720-0000.avg.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/2300-131720-0000.2stages.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/2300-131720-0000.gt.wav">
        </audio>
    </td>
  </tr>
</table>
</html>
### Text: "the greeting of the apostle is refreshing"
<html>
<table>
  <tr>
    <td>
      NARSiS<sub>base</sub>
    </td>
    <td>
      NARSiS<sub>avg</sub>
    </td>
    <td>
      NAT 2-stage
    </td>
    <td>
      Ground truth
    </td>
  </tr>
  <tr> 
    <td>
        <audio controls>
        <source src="audios/2830-3980-0040.vanilla.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/2830-3980-0040.avg.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/2830-3980-0040.2stages.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/2830-3980-0040.gt.wav">
        </audio>
    </td>
  </tr>
</table>
</html>
### Text: "i doubt whether branwell was maintaining himself at this time"
<html>
<table>
  <tr>
    <td>
      NARSiS<sub>base</sub>
    </td>
    <td>
      NARSiS<sub>avg</sub>
    </td>
    <td>
      NAT 2-stage
    </td>
    <td>
      Ground truth
    </td>
  </tr>
  <tr> 
    <td>
        <audio controls>
        <source src="audios/3575-170457-0056.vanilla.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/3575-170457-0056.avg.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/3575-170457-0056.2stages.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/3575-170457-0056.gt.wav">
        </audio>
    </td>
  </tr>
</table>
</html>
### Text: "well i'm going as an engineer you can go as one"
<html>
<table>
  <tr>
    <td>
      NARSiS<sub>base</sub>
    </td>
    <td>
      NARSiS<sub>avg</sub>
    </td>
    <td>
      NAT 2-stage
    </td>
    <td>
      Ground truth
    </td>
  </tr>
  <tr> 
    <td>
        <audio controls>
        <source src="audios/4507-16021-0049.vanilla.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/4507-16021-0049.avg.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/4507-16021-0049.2stages.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/4507-16021-0049.gt.wav">
        </audio>
    </td>
  </tr>
</table>
</html>
### Text: "he seemed to wait for her reply but as she made none he proceeded"
<html>
<table>
  <tr>
    <td>
      NARSiS<sub>base</sub>
    </td>
    <td>
      NARSiS<sub>avg</sub>
    </td>
    <td>
      NAT 2-stage
    </td>
    <td>
      Ground truth
    </td>
  </tr>
  <tr> 
    <td>
        <audio controls>
        <source src="audios/4992-23283-0008.vanilla.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/4992-23283-0008.avg.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/4992-23283-0008.2stages.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/4992-23283-0008.gt.wav">
        </audio>
    </td>
  </tr>
</table>
</html>
### Text: "there is no fear of that sir"
<html>
<table>
  <tr>
    <td>
      NARSiS<sub>base</sub>
    </td>
    <td>
      NARSiS<sub>avg</sub>
    </td>
    <td>
      NAT 2-stage
    </td>
    <td>
      Ground truth
    </td>
  </tr>
  <tr> 
    <td>
        <audio controls>
        <source src="audios/5105-28241-0007.vanilla.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/5105-28241-0007.avg.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/5105-28241-0007.2stages.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/5105-28241-0007.gt.wav">
        </audio>
    </td>
  </tr>
</table>
</html>
### Text: "these he gave to three of my brothers"
<html>
<table>
  <tr>
    <td>
      NARSiS<sub>base</sub>
    </td>
    <td>
      NARSiS<sub>avg</sub>
    </td>
    <td>
      NAT 2-stage
    </td>
    <td>
      Ground truth
    </td>
  </tr>
  <tr> 
    <td>
        <audio controls>
        <source src="audios/5142-33396-0004.vanilla.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/5142-33396-0004.avg.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/5142-33396-0004.2stages.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/5142-33396-0004.gt.wav">
        </audio>
    </td>
  </tr>
</table>
</html>
    
