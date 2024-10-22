---
title: 'Submit your design'
description: 'Get your design manufactured on Tiny Tapeout'
weight: 60
---

This guide will show you how to submit your design to Tiny Tapeout and understand the difference between tiles and chips.

## Prerequisites

Before you begin, make sure you have:

* A GitHub repository created from the latest Wokwi or Verilog Tiny Tapeout template.
* Passing GDS and Docs Actions in your repository. This ensures your design meets the required standards.

{{< figure src="images/passing_indicators.png" >}}

## Understanding Tiles and Chips

In Tiny Tapeout:

* **Tiles** are the individual designs on the chip. If your project gets more complex you can use more tiles.
* **Chips** are the actual physical chips manufactured. They contain all the tiles from all the participants.

## Step-by-Step Submission Guide

### Log In to Tiny Tapeout

* Go to: [app.tinytapeout.com](https://app.tinytapeout.com/)
* Click the **"Sign in with GitHub"** button.
* Authorize the application if prompted.

### Submit Your Repository

* Once logged in, press the **Create a new project** button.
* Copy and paste your GitHub repository URL into the Github field.

{{< figure src="images/submit_design_2.png" >}}
{{< figure src="images/submit_design_3.png" >}}

* Click the **"Create Project"** button.

### If you have a coupon code for a free tile

* During the submission, if you have a coupon for a free tile, paste the code in and press the 'apply' link.

### Complete the Submission Process

* You have now submitted your design, but it’s not yet part of the tapeout. 
* You have to submit a specific version of your design by pressing the **Submit a new revision** button.

{{< figure src="images/submit_design_4.png" >}}

* Your design will then be added to the Tapeout.
  
{{% notice warning %}}
Every time you make a change to your design you'll need to update the GDS and then submit a new revision. Designs can be changed up to the deadline.
{{% /notice %}}

### Congratulations!

You've successfully submitted your design to the Tiny Tapeout shuttle. We usually manufacture 4 chips per year, and we will include your design on the next chip.

## Important: Updating Your Submission

If you make any changes to your design after submission, you must update your submission.

### How to Update

1. Make changes to your design in your GitHub repository.
1. Ensure that all Actions (GDS and Docs) are passing.
1. If you only changed the Wokwi design, you'll have to [re-run the GitHub action](/guides/wokwi-to-gds/#tips).
1. Log back in to the submission portal: i.e. go to [app.tinytapeout.com](https://app.tinytapeout.com).
1. Select the project you want to update
1. Click the **Submit a new revision** button.

## Purchasing a PCB

If you'd like to receive a physical PCB with your chip you can either select that option when you submit your design for the first time or you can [buy a PCB and chip here](https://app.tinytapeout.com/prepurchase).
  
> **Note:** Only the first 80 boards are subsidized by [Efabless](https://efabless.com), so act fast!

## About Efabless

Efabless is our manufacturing partner, helping to make chip fabrication accessible. [Learn more about them here](https://efabless.com/).

## Updating Documentation After the Shuttle Ends

Once the shuttle run has ended, to update your documentation:

* Follow this guide: [Updating Docs Post-Shuttle](https://docs.google.com/document/d/16YdQM4Lh3ZazVcNXhO2Ssty5hzKGp0fj3FKmcbMlFZo/edit#heading=h.mcvyaz7a8clr).

## If you have time, try these next steps

Looking for ideas or want to see what others have created?

* Browse past runs: [Tiny Tapeout Runs](https://tinytapeout.com/runs/).
* Check out a sample datasheet: [Sample Datasheet PDF (TT07)](https://tinytapeout.github.io/tinytapeout-07/datasheet.pdf).