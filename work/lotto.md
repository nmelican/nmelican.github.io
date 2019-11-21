# P1 billion, anyone?
## How the UltraLotto 6/58 broke records in 2018

by Nathaniel Melican, City, University of London
------------------------------------------------

*Brief and notes: Research and write a data story demonstrating use of data journalism techniques and visualisation. This article is based on real data and information. All data used in this story came from the Philippine Charity Sweepstakes Office, and was accurate as of 5 January 2019. Currency conversion: £1=P66.56. Submitted for the Introduction to Data Journalism module at City, University of London.*

```html
<style media="screen" type="text/css">
  .caption {
    font-size: 8pt;
    font-style: italic;
  }
</style>
<img src="header image with the PCSO GM and the lotto winner" />

<p class="caption">Philippine Charity Sweepstakes Office (PCSO) General Manager Alexander Balutan (left) hands a cheque to one of the winners of the P1.18-billion UltraLotto Jackpot, whose identity is hidden behind a tarpaulin declaring, "I'm a Lotto jackpot winner," in this undated photo. The PCSO has stringent rules on lottery winner confidentiality, which led to this awkwardly-posed photo. Watching on the right is Deputy Spokesperson for the Office of the General Manager Florante Solmerin.<br />
Photo from PCSO social media</p>
```
____
```html
<!--what follows is the embed code for the Tableau visualisation-->
<div class='tableauPlaceholder' id='viz1572621797936' style='position: relative'>
  <noscript>
    <a href='#'>
      <img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ul&#47;Ultralotto&#47;UltraLotto658Thehardestdrawtocrack&#47;1_rss.png' style='border: none' />
    </a>
  </noscript>
  <object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' />
    <param name='embed_code_version' value='3' />
    <param name='site_root' value='' />
    <param name='name' value='Ultralotto&#47;UltraLotto658Thehardestdrawtocrack' />
    <param name='tabs' value='no' />
    <param name='toolbar' value='no' />
    <param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ul&#47;Ultralotto&#47;UltraLotto658Thehardestdrawtocrack&#47;1.png' />
    <param name='animate_transition' value='yes' />
    <param name='display_static_image' value='yes' />
    <param name='display_spinner' value='yes' />
    <param name='display_overlay' value='yes' />
    <param name='display_count' value='yes' />
  </object>
</div>
<script type='text/javascript'>
var divElement = document.getElementById('viz1572621797936');
var vizElement = divElement.getElementsByTagName('object')[0];
vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';
var scriptElement = document.createElement('script');
scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';
vizElement.parentNode.insertBefore(scriptElement, vizElement);
</script>
<!--end embed code-->

<p class="caption">Interact with the story of the UltraLotto 6/58 jackpot's rise and rise above or in <a href="https://public.tableau.com/views/Ultralotto/UltraLotto658Thehardestdrawtocrack?:embed=y&:display_count=yes&:toolbar=no&:origin=viz_share_link" target="_blank">Tableau</a>. Source: Philippine Charity Sweepstakes Office (PCSO) data</p>
```

### “I wanna be a billionaire so pretty bad.”

So goes Travie McCoy’s chart-topping debut single, aptly titled “Billionaire,” with that infamous refrain featuring Bruno Mars.

But what would you do if you had a billion’s worth of money? It might be hard to imagine your first move, but for a fortnight in October 2018, Filipinos were singing that tune, dreaming of tons of money, wishing luck on themselves, and queueing in droves to buy lottery tickets, as the country’s highest-paying but hardest-to-hit lottery draw broke records to reach a staggering jackpot of P1.18 billion (£15 million).

The P1.18-billion jackpot in the UltraLotto 6/58 draw, which was split by two winning bettors on 14 October, was the biggest that the Philippine Charity Sweepstakes Office (PCSO) has ever raised from any of the lottery draws that it runs.

```html
<img src="image of biggest lottery jackpots ever" />

<p class="caption">The UltraLotto's P1.18-billion jackpot as compared to the biggest jackpots for other lottery draws of the PCSO.<br />
Source: Philippine Charity Sweepstakes Office (PCSO) data</p>
```

The PCSO is a state-owned gaming corporation, which uses profits from lottery ticket sales and other gaming activities to fund state hospitals and health facilities, and to support indigent patients.

So just how long did it take for the jackpot to reach P1 billion? Data from the PCSO shows that the jackpot was last won on 16 February 2018 and rolled back to the lowest possible payout of P49.5 million (£75 million) for the 18 February draw. It took 34 weeks—two-thirds of the year—to reach the P1-billion mark.

```html
<img src="image of line graph of jackpot prize (y) plotted against the date (x)" />

<p class="caption">With a very slim chance of winning, it's not hard to see how jackpots of the UltraLotto can increase as it rolls over every week.<br />
Source: Philippine Charity Sweepstakes Office (PCSO) data</p>
```

The UltraLotto is notoriously hard to win, as there are over 40 million combinations of numbers to choose from—a one in 40 million chance of winning. At this rate, you are more likely to get hit by lightning (1 in 10 million), or even become an astronaut (1 in 12 million). Since its first draw on 8 February 2014, there have only been 15 winners drawn on 10 out of 488 draws.

But is there any chance that there are numbers that are drawn more frequently than others? Lotteries are games of chance, and drawn numbers are supposed to be random. An analysis of all numbers drawn from all UltraLotto draws since the game began in 2015 bears this out. There are differences in how many times numbers have been drawn, but nothing significant stands out. The most-drawn number was 6 (64 times), and the least-drawn number was 42 (35 times). All other numbers were drawn somewhere between 36 and 63 times.

```html
<img src="image of the lotto numbers most frequently drawn" />

<p class="caption">Despite variances in how many times each number has been drawn, the lottery is still purely a game of chance.<br />
Source: Philippine Charity Sweepstakes Office (PCSO) data</p>
```

And if you need more convincing that the numbers are drawn at random, just check out this scatterplot, which shows a noisy plot of all numbers drawn across time, with no discernible pattern.

Better keep betting and praying, then.#####

```html
<img src="image of scatterplot of all draw results" />

<p class="caption">No patterns emerge on this noisy scatterplot of all of the numbers drawn in the UltraLotto since it started.<br />
Source: Philippine Charity Sweepstakes Office (PCSO) data</p>
```
