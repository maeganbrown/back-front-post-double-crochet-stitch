---
layout: page
title: Basics
permalink: /Basics/
---

- [Choosing the correct hook size](#hook-size)
- [Holding yarn (for right-handers)](#hold-yarn)
- [The slip stitch](#slip-stitch)
- [The chain](#chain)
- [The double crochet stitch](#double-crochet)
- [Counting stitches](#count-stitches)
- [Identifying the posts in double crochet stitches](#identify-post)

# <a name="hook-size"></a>Choosing the correct hook size
Generally, you should select the hook size that is recommended on the yarn ball label. However, if you tend to make loose stitches, choosing a smaller hook size will help you create tighter stitches and vice versa. I personally like to select a hook that is one size smaller than the recommended one.
* A _hook_ refers to a crochet hook. They look like these: ![crochet-hook](/assets/crochet-hook.jpg)  
Crochet hooks are identified by their width (in mm) universally, but in the US, some are also identified by letter/number pairs. Here are some of the most common hooks:  
<center><table>
  {% for row in site.data.hook-sizes %}
    {% if forloop.first %}
    <tr>
      {% for pair in row %}
        <th>{{ pair[0] }}</th>
      {% endfor %}
    </tr>
    {% endif %}

    {% tablerow pair in row %}
      {{ pair[1] }}
    {% endtablerow %}
  {% endfor %}
</table></center>
 
* _Yarn weight_ refers to the thickness of a particular yarn. It is typically measured on a scale of 0 to 6, where 0 is the thinnest yarn.
    * The yarn weight (as well as the recommended hook size) are typically displayed in diagrams that resemble the following:  
![yarn-ball-detail](/assets/yarn-ball-detail.png)

# <a name="hold-yarn"></a>Holding yarn (for right-handers) 
There are two reasons why we wrap the yarn around our hand instead of just crocheting directly from the yarn ball.
* It allows us to control the yarn tension.
* It allows us to control the speed at which we feed in new yarn.

## To hold the yarn properly (for right-handers):
1. Find the end of the yarn.
1. Move the yarn tail to the right side of your working space.
1. Rest your left hand on the yarn at a point several inches away from the end of the yarn.
1. Slide left pinky finger under yarn.
1. Loop your finger over the yarn, so that the yarn fully circles your finger.
1. Pass the yarn tail over your left index finger.
1. Pinch the yarn tail between your left thumb and left middle or ring finger.  
1. Pick up the hook you have selected with your right hand.
1. Pass the hook under the yarn segment you are pinching.

![holding-yarn-properly](/assets/holding-yarn-properly.gif)

You are now properly holding the yarn. Take a moment to play with pulling yarn through your fingers.

# <a name="slip-stitch"></a>The slip stitch
The slip stitch will be the first stitch you make in your crochet projects. It is crucial to make because it acts as a stopping point that prevents your future stitches from unravelling.  

To make a slip stitch:
1. Hold the yarn properly.
1. Loop the hook in a full circle towards yourself, so that the yarn fully circles the hook.
1. Adjust your pinched fingers to hold the point where the yarn crosses itself.
1. Pass the hook around your working yarn from the left.
  * _Working yarn is the yarn segment between your index finger and the hook._
  * _This action is commonly referred to as __yarning over__._
1. Notice that the yarn appears to be in a 'Z'-like shape now.
1. Pull the top of the 'Z' down through the loop at the bottom of the 'Z'.
1. Tighten the knot.

![slip-stitch](/assets/slip-stitch.gif)

You have now successfully created a slip stitch!

# <a name="chain"></a>The chain
Creating a chain is necessary because other stitches must be worked __into__ something whereas a chain is indepedent from other stitches. Chains are also frequently used to establish the physical length of a project.

To create a chain:
1. If you are just starting the project, make a slip stitch. Otherwise, skip to step 2.
1. Yarn over.
1. Pull the top yarn through the bottom loop.
  * _This action is commonly referred to as __pulling through__._
  * _For example, the above instruction is equivalent to: "Pull through the loop on the hook."_

![chaining](/assets/chaining.gif)

Congratulations! You've successfully created a chain. To continue making chains, repeat steps 2-3 as many times as needed.

# <a name="double-crochet"></a>The double crochet stitch
To make a double crochet stitch:
1. If you are just starting the project, make sure you create a few chains.
  * _If you're unsure how many to make, ten is a decent number for practice._
1. Yarn over.
1. Insert hook into the first chain from the hook.
1. Yarn over.
1. Pull up a loop.
1. Yarn over.
1. Pull through the top two loops on the hook.
1. Yarn over.
1. Pull through the last two loops on the hook.

![double-crochet](/assets/double-crochet.gif)

You have completed one double crochet stitch! If you would like to continue making double crochet stitches, repeat steps 2-9 as many times as needed.

# <a name="count-stitches"></a>Counting stitches
Counting your stitches frequently is important to ensure you're not skipping any stitches accidentally. It's good practice to count your stitches after every few rows to discover any mistakes early.

In order to count stitches, start from the stitch closest to your hook and count the tops of individual stitches until you reach the end of the row. The following picture shows how we can identify individual stitches by looking for the "v's" created at the top of each stitch:  
![counting-stitches](/assets/counting-stitches.gif)

The tenth stitch was technically the first stitch created on its row. Due to this, it had to "create" its own height and therefore it looks different. All subsequent stitches of the row (stitches 9 through 1) already had their height established by a preceding stitch and thus look alike.

# <a name="identify-post"></a>Identifying the posts in double crochet stitches
Each double crochet stitch has a corresponding post. If the "v's" discussed in the [Counting stitches](#count-stitches) section are though of as the "head" of the stitch, then the posts are the "body" of the stitch.

The posts can be easily identified by gripping each side of your row of double crochet stitches and *stretching*. This will expose gaps on either side of the posts in the same locations as the dotted lines below.

![identifying-posts](/assets/identifying-posts.png)

This is the same crocheted swatch shown in the [Counting stitches](#count-stitches) section, so we already know that it had 10 stitches. If you count the arrows in the image above, you'll find that the number of posts corresponds to the number of stitches. After all, every head needs a body.
