# Single-stage TTS with Masked Audio Token Modeling and Semantic Knowledge Distillation

This is the demonstration page of the paper "Single-stage TTS with Masked Audio Token Modeling and Semantic Knowledge Distillation" with some selected samples generated with the proposed methods.

## Info

### Abstract

Audio token modeling has become a powerful framework for speech synthesis, with two-stage approaches employing semantic tokens remaining prevalent. In this paper, we aim to simplify this process by introducing a semantic knowledge distillation method that enables high- quality speech generation in a single stage. Our proposed model improves speech quality, intelligibility, and speaker similarity compared to a single- stage baseline. Although two-stage systems still lead in intelligibility, our model significantly narrows the gap while delivering comparable speech quality. These findings showcase the potential of single-stage models to achieve efficient, high-quality TTS with a more compact and streamlined architecture.

## Demos

The following examples are selected from the listening test described in the paper, which are generated from LibriSpeech test-clean subset. The models to compare include the one-stage model without semantic knowledge distillation (NARSiS<sub>base</sub>), one-stage model with semantic knowledge distillation (NARSiS<sub>avg</sub>), and the two-stage model (NAR 2-stage).

#### Text: "this evening they all said"
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
      NAR 2-stage
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
#### Text: "the paris plant like that at the crystal palace was a temporary exhibit"
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
      NAR 2-stage
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
#### Text: "the greeting of the apostle is refreshing"
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
      NAR 2-stage
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
#### Text: "i doubt whether branwell was maintaining himself at this time"
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
      NAR 2-stage
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
#### Text: "well i'm going as an engineer you can go as one"
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
      NAR 2-stage
    </td>
    <td>
      Ground truth
    </td>
  </tr>
  <tr> 
    <td>
        <audio controls>
        <source src="audios/4970-29093-0014.vanilla.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/4970-29093-0014.avg.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/4970-29093-0014.2stages.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/4970-29093-0014.gt.wav">
        </audio>
    </td>
  </tr>
</table>
</html>
#### Text: "he seemed to wait for her reply but as she made none he proceeded"
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
      NAR 2-stage
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
#### Text: "there is no fear of that sir"
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
      NAR 2-stage
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
#### Text: "these he gave to three of my brothers"
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
      NAR 2-stage
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
#### Text: "she saw that the bed was gilded and so rich that it seemed that of a prince rather than of a private gentleman"
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
      NAR 2-stage
    </td>
    <td>
      Ground truth
    </td>
  </tr>
  <tr> 
    <td>
        <audio controls>
        <source src="audios/5639-40744-0013.vanilla.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/5639-40744-0013.avg.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/5639-40744-0013.2stages.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/5639-40744-0013.gt.wav">
        </audio>
    </td>
  </tr>
</table>
</html>
#### Text: "he makes it sort of cozier"
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
      NAR 2-stage
    </td>
    <td>
      Ground truth
    </td>
  </tr>
  <tr> 
    <td>
        <audio controls>
        <source src="audios/6930-76324-0018.vanilla.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/6930-76324-0018.avg.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/6930-76324-0018.2stages.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/6930-76324-0018.gt.wav">
        </audio>
    </td>
  </tr>
</table>
</html>
#### Text: "he has given them with too much grace not to have others still to give if they are required which is the case at the present moment"
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
      NAR 2-stage
    </td>
    <td>
      Ground truth
    </td>
  </tr>
  <tr> 
    <td>
        <audio controls>
        <source src="audios/7127-75946-0006.vanilla.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/7127-75946-0006.avg.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/7127-75946-0006.2stages.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/7127-75946-0006.gt.wav">
        </audio>
    </td>
  </tr>
</table>
</html>
#### Text: "the hawk embittered by the loss of his first quarry had become as dogged in pursuit as a weasel not to be shaken off or evaded or deceived"
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
      NAR 2-stage
    </td>
    <td>
      Ground truth
    </td>
  </tr>
  <tr> 
    <td>
        <audio controls>
        <source src="audios/7176-88083-0022.vanilla.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/7176-88083-0022.avg.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/7176-88083-0022.2stages.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/7176-88083-0022.gt.wav">
        </audio>
    </td>
  </tr>
</table>
</html>
#### Text: "but your power is so superior to any that i can advance as to make us here feel that there is no disgrace in yielding to it"
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
      NAR 2-stage
    </td>
    <td>
      Ground truth
    </td>
  </tr>
  <tr> 
    <td>
        <audio controls>
        <source src="audios/8455-210777-0033.vanilla.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/8455-210777-0033.avg.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/8455-210777-0033.2stages.wav">
        </audio>
    </td>
    <td>
        <audio controls>
        <source src="audios/8455-210777-0033.gt.wav">
        </audio>
    </td>
  </tr>
</table>
</html>
    
