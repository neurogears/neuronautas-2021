---
layout: slides
title: Introduction to Bonsai
---

<section data-markdown data-separator="^\n---\n$" data-separator-vertical="^\n--\n$">
<script type="text/template">

![Bonsai](./assets/images/bonsai-lettering.svg)

### Introduction to Bonsai
[neuronautas.github.io/intro-bonsai](https://neuronautas.github.io/intro-bonsai)

<table style="width: 100%;">
  <tr>
    <th style="vertical-align: middle; width: 33%; height: 100px; padding-left: 100px">
      <img alt="NeuroGEARS" src="./assets/images/neurogears.svg"/>
    </th>
    <th style="vertical-align: middle; width: 33%; height: 100px; align: center">
      <img alt="NeuroGEARS" src="./assets/images/neuronautas.svg"/>
    </th>
    <th style="vertical-align: middle; width: 33%; height: 100px; align: right">
      <img alt="Neuronautas" src="./assets/images/cf.png"/>
    </th>
  </tr>
</table>

---

### Neuroscience needs makers & hackers

On the nature of field neuroscience tools:

* Accessible
<!-- .element: class="fragment" data-fragment-index="1" -->
<!-- Accessible both in the sense that everyone can use... (so many walks of life in neuroscience) -->
<!-- ... but also in the sense that they can be understood. (using a tool with understanding is transformative) -->
* Forward-thinking
<!-- .element: class="fragment" data-fragment-index="2" -->
<!--  We want our tools to push the bar of what we can measure... (vastly underpowered tools) -->
<!--  ... but equally importantly we want them to challenge and surprise us. (surprise is the basis of discovery) -->
* Versatile
<!-- .element: class="fragment" data-fragment-index="3" -->
<!--  We need to combine tools in all sorts of ways... (crazy neuro experiments) -->
<!--  ... but also be inclusive to modifications and new demands -->

---

![Devices compatible with Bonsai](./assets/images/devices.jpg)

---

![Applications in Neuroscience](./assets/images/bonsai-applications.svg)

---

![Bonsai workflow editor](./assets/images/editor.jpg)

---

<!-- .element: data-transition="default none" -->
#### A metaphor for observable sequences

<img alt="Nasa twitter account" src="./assets/images/nasatwitter.jpg" width="400"/>

--

<!-- .element: data-transition="none" -->
#### A metaphor for observable sequences

<img alt="Webcam twitter account" src="./assets/images/webcamtwitter.jpg" width="400"/>

---

<!-- .element: data-transition="default none" -->
![Workflow](./assets/images/cameracapture.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/framepicker-marblecanvas.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="default none" -->
![Workflow](./assets/images/graycam.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/graycam-marble.svg)
<!-- .element: class="fragment" style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="default none" -->
![Workflow](./assets/images/framepicker-key.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/framepicker-marblecanvas.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="default none" -->
![Workflow](./assets/images/framepicker-capture.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/cameracapture-marble.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](./assets/images/framepicker-grayscale.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/grayscalefile.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](./assets/images/framepicker-grayscale.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/grayscaletransform.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](./assets/images/framepicker-sample.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/grayscalesample.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](./assets/images/framepicker-saveimage.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/saveimage.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](./assets/images/framepicker-saveimage.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/saveimagesink.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](./assets/images/framepicker-key.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/framepicker-marblecanvas.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
![Workflow](./assets/images/framepicker.svg)
<!-- .element: style="display: inline-block; vertical-align: middle;" -->
![Marble diagram](./assets/images/conditionkey.svg)
<!-- .element: class="fragment" style="display: inline-block; vertical-align: middle;" -->

---

<!-- .element: data-transition="default none" -->
##### Operator Categories

![Operator categories](./assets/images/categories-simple.svg)
<!-- .element: style="padding: 30px; display: inline-block; vertical-align: middle;" -->

--

<!-- .element: data-transition="none" -->
##### Operator Categories

![Operator categories](./assets/images/categories.svg)
<!-- .element: style="padding: 30px; display: inline-block; vertical-align: middle;" -->

---

###### Skip

![Skip](./assets/images/skip.svg)

---

###### Take

![Take](./assets/images/take.svg)

---

###### Delay

![Delay](./assets/images/delay.svg)

---

###### Repeat

![Delay](./assets/images/repeat.svg)

---

###### Zip

![Zip](./assets/images/zip.svg)

---

### Sharing observable sequences

![Branching](./assets/images/branching-simple.svg)
<!-- .element: style="display: inline-block; vertical-align: top;" -->
![Subjects (Publish)](./assets/images/subjects-publish-simple.svg)
<!-- .element: class="fragment" style="display: inline-block; vertical-align: top; padding-left: 120px;" -->

---

<!-- .element: data-transition="default none" -->
###### Transform

![Transform](./assets/images/transform.svg)

--

<!-- .element: data-transition="default none" -->
###### Select

![Select](./assets/images/select.svg)

--

<!-- .element: data-transition="none default" -->
###### SelectMany

![SelectMany](./assets/images/selectmany.svg)

--

<!-- .element: data-transition="none default" -->
###### SelectMany: Play audio on cue

![SelectMany](./assets/images/selectmany-playsound-1.svg)

--

<!-- .element: data-transition="none default" -->
###### SelectMany: Play audio on cue

![SelectMany](./assets/images/selectmany-playsound-2.svg)

---

### Representing discrete states

**State**
<!-- .element: class="fragment" data-fragment-index="1" style="display: inline-block; vertical-align: middle;" -->

<small>"the particular condition that someone or something is in at a specific time"</small>
<!-- .element: class="fragment" data-fragment-index="1" style="display: inline-block; vertical-align: middle;" -->
<small>"a physical condition as regards internal or molecular form or structure"</small>
<!-- .element: class="fragment" data-fragment-index="2" style="display: inline-block; vertical-align: middle;" -->

**Event**
<!-- .element: class="fragment" data-fragment-index="3" style="display: inline-block; vertical-align: middle;" -->

<small>"a thing that happens or takes place, especially one of importance"</small>
<!-- .element: class="fragment" data-fragment-index="3" style="display: inline-block; vertical-align: middle;" -->
<small>"a single occurrence of a process, e.g. the ionization of one atom"</small>
<!-- .element: class="fragment" data-fragment-index="4" style="display: inline-block; vertical-align: middle;" -->

<small>source: <a href="https://en.oxforddictionaries.com/">Oxford English Living Dictionaries</a></small>
<!-- .element: class="fragment" data-fragment-index="1" style="display: inline-block; position: absolute; right: 0px;" -->

--

#### Working Definition

**State** → Extended

**Event** → Punctate

---

<!-- .element: data-transition="default none" -->
![SelectMany](./assets/images/selectmany-events-hidden.svg)

--

<!-- .element: data-transition="none none" -->
![SelectMany](./assets/images/selectmany-events-in.svg)

--

<!-- .element: data-transition="none none" -->
![SelectMany](./assets/images/selectmany-states.svg)

--

<!-- .element: data-transition="none default" -->
![SelectMany](./assets/images/selectmany-events-out.svg)

---

![Bonsai](./assets/images/bonsai-lettering.svg)

### Questions?
[neuronautas.github.io/intro-bonsai](https://neuronautas.github.io/intro-bonsai)
<table style="width: 100%;">
  <tr>
    <th style="vertical-align: middle; width: 33%; height: 100px; padding-left: 100px">
      <img alt="NeuroGEARS" src="./assets/images/neurogears.svg"/>
    </th>
    <th style="vertical-align: middle; width: 33%; height: 100px; align: center">
      <img alt="NeuroGEARS" src="./assets/images/neuronautas.svg"/>
    </th>
    <th style="vertical-align: middle; width: 33%; height: 100px; align: right">
      <img alt="Neuronautas" src="./assets/images/cf.png"/>
    </th>
  </tr>
</table>

</script>
</section>