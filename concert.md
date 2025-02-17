# Concert

```{image} ./assets/xenakis-concert-banner.jpg
:name: concert-banner
```

---

In honor of the 100th birthday of composer and architect Ιάννης Ξενάκης there will be a concert on tuesday, **2022-10-25 at 19:00** at the parking garage of the IMM Düsseldorf.
The program consists of compositions by Xenakis himself as well as works that were inspired by him.

## Aachorripsis (recalculated)

*Live electronics for 7 channels (7')*

```{figure} ./assets/aachorripsis.png
:name: Aachoripsis

The original calculation matrix for Aachoripsis - taken from {cite}`Xenakis1992`.
```

```{figure} ./assets/aachorripsis-recalculated.png
:name: Aachoripsis recalculated

The re-implementation of density matrix of Aachoripsis in SuperCollider.
```

*Aachoripsis* (1957) is the second composition by Iannis Xenakis which is driven by stochastic calculations.
For this concert Iosif Tournas and Dennis Scheiba re-implemented the idea of using the poisson probability distribution to distribute musical events in a score using the notes which Xenakis wrote in Formalized Music {cite}`Xenakis1992` and use this musical events to 
trigger events on two modular systems.

The poisson distribution is often used to model the probability of events that will happen within a fixed time slot if these events should occur at an average rate.
Examples of application of the poisson distribution are how many popcorns will pop over time when put into a microwave (they don't pop all together at the exact same time, yet they all happen around the same time) or radioactive decay.

Xenakis about *Aachoripsis* in {cite}`Xenakis1992`:

> Now the question is, when heard a number of times, will this music keep its surprise effect? Will it not change into a set of foreseeable phenomena through the existence of memory, despite the fact that the law of frequencies has been derived from the laws of chance?
>
> In fact, the data will appear aleatory only at the first hearing. Then, during successive rehearings the relations between the events of the sample ordained by "chance" will form a network, which will take on a definite meaning in the mind of the listener, and will initiate a special "logic," a new cohesion capable of satisfying his intellect as well as his aesthetic sense; that is, if the artist has a certain flair.

The source code for the performance is located at <https://github.com/capital-G/Aachorripsis>.

## TrainsGrainsRains

*Live computer algorithm, 8 channels (15')*

By Jiawen Wang.

```{figure} ./assets/trainsgrainsrains.png
:name: trainsgrainsrains

trainsgrainsrains
```

## From two roots

*Quadrophonic computermusic (20')*

By Shuoxin Tan

```{figure} ./assets/two-roots.jpg
:name: From two roots
:scale: 50%

$25 \sqrt{5}$ vs. $12 \sqrt{2}$
```

Die algorithmische Computermusik-Komposition basiert auf zwei mathematischen Zahlen (Wurzeln), die für zwei unterschiedliche gleichstufig temperierte Stimmungssysteme stehen: $12 \sqrt{2}$ aus der traditionellen Stimmung und $25 \sqrt{5}$ aus der elektronischen Musikkomposition *Studie II* von Karlheinz Stockhausen.
Anhand der Programmiersprache SuperCollider wird diese winzige, kaum wahrnehmbare Differenz von zwei Wurzeln auf die Mikrotonalität angewendet und die Zahlen als Grundproportionen aller Klangcharaktere wie Frequenz, Hüllkurve, Tondauer, Lautstärke usw. mittels Sinustöne vertont.

## Voyage Absolu Des Unari Vers Andromède

*Fixed media, stereo (16')*

```{figure} ./assets/andromeda.jpg
:name: Andromeda

Drawing for synthetisation of Voyage absolu des Unari vers Andromède
```

A lesser known electro-acoustic composition by Xenakis which uses the UPIC program for synthesis.
This allows for a more controlled approach than the later GENDY algorithm.

> The piece was solicited and commisioned by Dr. Paul Eubel, Director of the Goethe Institute in Japan, for the inauguration of the International Exposition of Paper Kites, on 1 April 1989.
> It is dedicated to him.
> The piece is about a space voyager far in the future, toward the galaxy of Andromeda, with episodes while crossing the spaces between the stars.
> The score consists of pages designed on the UPIC[^upic] at CEMAMu.

[^upic]: UPIC (Unite Polyagoqique Informatique du CEMAMu) is a computer system which lets one compose music simply by the graphic design of pages. The UPIC system was created and produced at CEMAMu.

## OH⁻ × O²H⁻

*Live electronics for 8 speakers (9'26")*

By Julian Rohrhuber.

When a molecule rotates alone in space, it does not continue to do so forever. Because its center of mass is never identical with the center of the electric charge, its rotation causes a movement of charge, which leads to an emission of light and a slowing down of the rotation. The emission is not continuous, however, but can occur only in specific frequency steps. These steps result from the mathematical combinatoric of rotational modes and the stretching and elasticity of the molecule. This process, thinned out and multiplied, is the light we can detect in interstellar nebula. Spectroscopy brings about the rich structure of the interaction between physical properties and mathematical properties of rotation groups, which also make an important ingredient of the compositions by Xenakis.

The piece OH⁻ × O²H⁻ explores the spectra of two very similar two-atom molecules formed by oxygen (O), one with hydrogen (H) and one with its isotope deuterium (²H), which merely adds an extra neutron to the proton. Over the time of the piece, we traverse the far infrared spectra from high to low, frequency projected into time. We hear a crossing of the two spectra: lines of one spectrum trigger resonances in selected parts of the other, transposed into the audible range by the hydrogen emission line.

Special thanks to Volker Ossenkopf-Okada.

## Break

Around 20 minutes.

## Persepolis

> We bear the light of the earth

*Fixed media for 8 channels (60')*

```{figure} ./assets/persepolis.jpg
:name: Persepolis

Photo from *Polytope de Persepolis* spectacle (from {cite}`Xenakis_Kanach_2008`)
```

As a prelude to *Persepolis* the composition *Diamorphoses* (1957, 7') will be played as in the original presentation.

Commissioned in 1971 by the Persian Shah for the celebration of the 2500th anniversary of the persian empire, the piece was part of a multimedia performance (aka Polytopes) which premiered in in the historical place of Persepolis near Shiraz in nowadays Iran.
The performance at night included bonfires, projector lights, two red leaser beams scanning the ruins, searchlights, 130 children walking around with torches and 59 loudspeakers to project the music into the ruins of Persepolis.

Xenakis was criticized in France for participating in a festival organized by the shah.
He responded to this with an open letter in *Le Monde* on 1971-12-14, cited from {cite}`Xenakis_Kanach_2008`

> [...]
> 
> I am a wandering man, an "alien citizen" of every country (in art as well) and my hardened conscience - nourished either
> by the flames of the Greek resistance (which was betrayed from its conception and over the years by the Soviets, the Allies and the Greeks themselves)
> or by the desperate efforts of my music - alone, may guide me towards light or toward death.
> 
> For me the worst and most shameful injustice is the torture and execution (ether secretly or overtly) of men and women, even if they are "terrorists".
> This is why I have always been involved, and will continue to be, in protests and actions against dynasties and tyrants, be they military, heads of State, presidents, shahs, or kings.
> It is in my nature.
