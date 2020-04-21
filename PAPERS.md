## [Strang Lecture 8: Solving Ax = b: Row Reduced Form R](https://www.youtube.com/watch?v=9Q1q7s1jTzU)
### Gilbert Strang

* We'll reuse our example matrix to explore <img src="/tex/6ffa573707fca115cad7b243d91a7109.svg?invert_in_darkmode&sanitize=true" align=middle width=50.69621369999999pt height=22.831056599999986pt/>:

<p align="center"><img src="/tex/695d6dcfed1fa253519b8dd53016e86e.svg?invert_in_darkmode&sanitize=true" align=middle width=187.03206225pt height=59.1786591pt/></p>

* Let's use an augmented matrix to deal with the right hand side and do
  elimination:

<p align="center"><img src="/tex/4545a8ad84c6167498141eb954e12ead.svg?invert_in_darkmode&sanitize=true" align=middle width=159.6349128pt height=59.1786591pt/></p>

* End up with, the condition for a solution is <img src="/tex/225d150b596970a35004bd81427462a5.svg?invert_in_darkmode&sanitize=true" align=middle width=125.57051265pt height=22.831056599999986pt/>
  (e.g. <img src="/tex/5f5355935f9d9f19d9ddc9f2bf9b91fc.svg?invert_in_darkmode&sanitize=true" align=middle width=81.02725454999998pt height=24.65753399999998pt/>):

<p align="center"><img src="/tex/4b4a6ca02aaa1b4fddf64e514525d8e0.svg?invert_in_darkmode&sanitize=true" align=middle width=233.24198205pt height=59.1786591pt/></p>

* Solvability: a condition on <img src="/tex/4bdc8d9bcfb35e1c9bfb51fc69687dfc.svg?invert_in_darkmode&sanitize=true" align=middle width=7.054796099999991pt height=22.831056599999986pt/>.  <img src="/tex/6ffa573707fca115cad7b243d91a7109.svg?invert_in_darkmode&sanitize=true" align=middle width=50.69621369999999pt height=22.831056599999986pt/> is solvable when <img src="/tex/4bdc8d9bcfb35e1c9bfb51fc69687dfc.svg?invert_in_darkmode&sanitize=true" align=middle width=7.054796099999991pt height=22.831056599999986pt/> is in the
  columnspace of <img src="/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/>, <img src="/tex/34e5f1f13b2812eee1b9520c4affa446.svg?invert_in_darkmode&sanitize=true" align=middle width=38.038868999999984pt height=24.65753399999998pt/>. Alternatively, if a combination of the rows of
  <img src="/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/> give the zero row, then the same combination of the components of <img src="/tex/4bdc8d9bcfb35e1c9bfb51fc69687dfc.svg?invert_in_darkmode&sanitize=true" align=middle width=7.054796099999991pt height=22.831056599999986pt/>
  have to give a zero.

* To find complete solution to <img src="/tex/6ffa573707fca115cad7b243d91a7109.svg?invert_in_darkmode&sanitize=true" align=middle width=50.69621369999999pt height=22.831056599999986pt/>:

  * Find a particular solution. One way to find a particular solution: set all
    free variables to zero and then solve for pivot variables.

  <p align="center"><img src="/tex/43d8a479203a8cb80758dbd37bae51e1.svg?invert_in_darkmode&sanitize=true" align=middle width=98.27185829999999pt height=78.9048876pt/></p>

  * Add in the nullspace <img src="/tex/d7084ce258ffe96f77e4f3647b250bbf.svg?invert_in_darkmode&sanitize=true" align=middle width=17.521011749999992pt height=14.15524440000002pt/> (aka special solutions).

* The complete solution to <img src="/tex/6ffa573707fca115cad7b243d91a7109.svg?invert_in_darkmode&sanitize=true" align=middle width=50.69621369999999pt height=22.831056599999986pt/> is <img src="/tex/2bc7a0501b098605f46d03e2abb36260.svg?invert_in_darkmode&sanitize=true" align=middle width=139.20797055pt height=19.1781018pt/>

<p align="center"><img src="/tex/276344100dbd931ddd3dea5278002148.svg?invert_in_darkmode&sanitize=true" align=middle width=362.17469475pt height=78.9048876pt/></p>

* Note <img src="/tex/ca2029a5cbe6fc73d2db721fec0638df.svg?invert_in_darkmode&sanitize=true" align=middle width=419.93166765pt height=24.65753399999998pt/>.

* <img src="/tex/773dc52501a09d3dc40596571a2321dd.svg?invert_in_darkmode&sanitize=true" align=middle width=15.26963954999999pt height=14.15524440000002pt/> in this case is a subspace (the nullspace) shifted by the
  <img src="/tex/0957a9bbf01d2ea5f621f1d068d404d9.svg?invert_in_darkmode&sanitize=true" align=middle width=16.17146519999999pt height=14.15524440000002pt/>.  Instead of going through zero, the subspace goes through
  <img src="/tex/0957a9bbf01d2ea5f621f1d068d404d9.svg?invert_in_darkmode&sanitize=true" align=middle width=16.17146519999999pt height=14.15524440000002pt/>.

* Relations between rank <img src="/tex/89f2e0d2d24bcf44db73aab8fc03252c.svg?invert_in_darkmode&sanitize=true" align=middle width=7.87295519999999pt height=14.15524440000002pt/> in a <img src="/tex/205995f88b807b2f5268f7ef4053f049.svg?invert_in_darkmode&sanitize=true" align=middle width=44.39116769999999pt height=19.1781018pt/> matrix:

  * <img src="/tex/9dad75ceef24a34ae5a4707a7d1571d5.svg?invert_in_darkmode&sanitize=true" align=middle width=44.22368609999999pt height=20.908638300000003pt/>
  * <img src="/tex/e5a277555371ce571a0d3f06d3ad7ed7.svg?invert_in_darkmode&sanitize=true" align=middle width=39.65746289999999pt height=20.908638300000003pt/>

* Full column rank <img src="/tex/e6b88fbaec17edf03d3fd1adf98db331.svg?invert_in_darkmode&sanitize=true" align=middle width=39.65746289999999pt height=14.15524440000002pt/>: no free variables, nullspace is only the zero
  vector, one or zero solutions to <img src="/tex/6ffa573707fca115cad7b243d91a7109.svg?invert_in_darkmode&sanitize=true" align=middle width=50.69621369999999pt height=22.831056599999986pt/>.  Matrix will look tall and thin.
  Each zero row will be an additional condition on <img src="/tex/4bdc8d9bcfb35e1c9bfb51fc69687dfc.svg?invert_in_darkmode&sanitize=true" align=middle width=7.054796099999991pt height=22.831056599999986pt/>.

* Full row rank <img src="/tex/972a93691ff5ceb688f5e875b61f528d.svg?invert_in_darkmode&sanitize=true" align=middle width=44.22368609999999pt height=14.15524440000002pt/>: One or many solutions for every <img src="/tex/4bdc8d9bcfb35e1c9bfb51fc69687dfc.svg?invert_in_darkmode&sanitize=true" align=middle width=7.054796099999991pt height=22.831056599999986pt/> (depending if
  there are free variables.  There will be <img src="/tex/48d45f061bd81cbb30840cc309e2b25b.svg?invert_in_darkmode&sanitize=true" align=middle width=104.13982095pt height=19.1781018pt/> free variables). Matrix
  will be short and fat.  <img src="/tex/079bfec7814e7f4bcbae5a5e2830bb51.svg?invert_in_darkmode&sanitize=true" align=middle width=46.21760714999999pt height=17.723762100000005pt/> results in free variables.

* Full row and column rank <img src="/tex/c6578e573264528b0d6927ee0c7a1176.svg?invert_in_darkmode&sanitize=true" align=middle width=76.00819379999999pt height=14.15524440000002pt/>.  Square matrix and invertible, one
  solution for every b. Row reduced echelon form is the identity matrix.

* If <img src="/tex/d65635677d427f79f5afec59fb1e8022.svg?invert_in_darkmode&sanitize=true" align=middle width=44.22368609999999pt height=17.723762100000005pt/> and <img src="/tex/797f7e1e586399c71e8b56b04c7af670.svg?invert_in_darkmode&sanitize=true" align=middle width=39.65746289999999pt height=17.723762100000005pt/>, then you will have 0 solutions (if the conditions of
  the zero row are not satisifed) or infinite solutions if the conditions of
  the zero row are satisfied.


## [Strang Lecture 7: Solving Ax = 0: Pivot Variables, Special Solutions](https://www.youtube.com/watch?v=VqP2tREMvt0)
### Gilbert Strang

* Use elimination to solve a <img src="/tex/5b4cf7163dd6f95ba26235a3efa57ac2.svg?invert_in_darkmode&sanitize=true" align=middle width=36.52961069999999pt height=21.18721440000001pt/> rectangular matrix (<img src="/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/>):

<p align="center"><img src="/tex/bebe32224cc9eb809d4cdde8d74f24ac.svg?invert_in_darkmode&sanitize=true" align=middle width=128.76731835pt height=59.1786591pt/></p>

* During elimination:
    * Nullspace does not change
    * Solutions do not change
    * Columnspace **IS** changing
    * Rowspace does not change (not explicitly mentioned, but assume so)

* Result of elimination (<img src="/tex/6bac6ec50c01592407695ef84f457232.svg?invert_in_darkmode&sanitize=true" align=middle width=13.01596064999999pt height=22.465723500000017pt/>):

<p align="center"><img src="/tex/45a25ec04e9bb57f0e505f6908eb87ef.svg?invert_in_darkmode&sanitize=true" align=middle width=120.5481156pt height=59.1786591pt/></p>


* No pivot in second column means it's free (a combo of other columns)

* 2 total pivots; they are 1 at (1,1) and 2 at (2,3)

* The result of elimination is in upper echelon form (<img src="/tex/6bac6ec50c01592407695ef84f457232.svg?invert_in_darkmode&sanitize=true" align=middle width=13.01596064999999pt height=22.465723500000017pt/>)

* Rank of matrix == pivots == 2 in this example.

* You can solve <img src="/tex/2fe657088322d47b689cd44cc71ccd05.svg?invert_in_darkmode&sanitize=true" align=middle width=52.54776779999999pt height=22.465723500000017pt/>, same solutions as <img src="/tex/2b71965bdc17323260ed22a8cc29538d.svg?invert_in_darkmode&sanitize=true" align=middle width=51.86062694999999pt height=22.465723500000017pt/>

* 2 pivot columns, 2 free columns

* You can assign any number to the free columns and then solve the equations
  for the pivots columns.

* Assign <img src="/tex/56139c2ecb22056c1ab58d6e6fc736a1.svg?invert_in_darkmode&sanitize=true" align=middle width=46.90628744999999pt height=21.18721440000001pt/> and <img src="/tex/face1f7a70bce3be1526cc862d0b9567.svg?invert_in_darkmode&sanitize=true" align=middle width=46.90628744999999pt height=21.18721440000001pt/> to the free variables and solve for <img src="/tex/277fbbae7d4bc65b6aa601ea481bebcc.svg?invert_in_darkmode&sanitize=true" align=middle width=15.94753544999999pt height=14.15524440000002pt/> and
  <img src="/tex/2c52641cc5fa73cbbdf887c89d82f0de.svg?invert_in_darkmode&sanitize=true" align=middle width=15.94753544999999pt height=14.15524440000002pt/>.  Note <img src="/tex/9ff44075699a748a2691b4dabf6780eb.svg?invert_in_darkmode&sanitize=true" align=middle width=59.69172164999999pt height=21.18721440000001pt/> and <img src="/tex/1412bdb3a4c77853bafc5e9e1b7150e5.svg?invert_in_darkmode&sanitize=true" align=middle width=46.90628744999999pt height=21.18721440000001pt/> after back subbing.  This is a vector in
  the nullspace and any multiple of it is in the nullspace.

* You have two free variables, so you need another vector in the nullspace.
  Now Assign <img src="/tex/3b556ebecf31f20220e296e4687393a3.svg?invert_in_darkmode&sanitize=true" align=middle width=46.90628744999999pt height=21.18721440000001pt/> and <img src="/tex/fb6f7317d69927ab9949587450b52cd8.svg?invert_in_darkmode&sanitize=true" align=middle width=46.90628744999999pt height=21.18721440000001pt/> to the free variables and solve for <img src="/tex/277fbbae7d4bc65b6aa601ea481bebcc.svg?invert_in_darkmode&sanitize=true" align=middle width=15.94753544999999pt height=14.15524440000002pt/>
  and <img src="/tex/2c52641cc5fa73cbbdf887c89d82f0de.svg?invert_in_darkmode&sanitize=true" align=middle width=15.94753544999999pt height=14.15524440000002pt/>.  Note <img src="/tex/bda947926e3a56a7e1f79bf2d7d9c985.svg?invert_in_darkmode&sanitize=true" align=middle width=46.90628744999999pt height=21.18721440000001pt/> and <img src="/tex/6815dc5c67a03ae13e30eb0b4a95d2c7.svg?invert_in_darkmode&sanitize=true" align=middle width=59.69172164999999pt height=21.18721440000001pt/> after back subbing.  This is anonter
  vector in the nullspace and any multiple of it is in the nullspace.

* Any linear combination of those two vectors are in the nullspace.  You'll get
  one vector in the nullspace for each free column.


<p align="center"><img src="/tex/f49c3fd306ccbf36ab5d041a67f507e3.svg?invert_in_darkmode&sanitize=true" align=middle width=315.03822405pt height=78.9048876pt/></p>

* Rank is equal to the pivot variable count.  Free variables is <img src="/tex/f7ac410dd4413138a6d3f58028ae8c58.svg?invert_in_darkmode&sanitize=true" align=middle width=42.566541599999994pt height=22.465723500000017pt/> for an
  <img src="/tex/205995f88b807b2f5268f7ef4053f049.svg?invert_in_darkmode&sanitize=true" align=middle width=44.39116769999999pt height=19.1781018pt/> matrix.

* Finding the nullspace: Do elimination.  Set each free variable to one (and
  others to zero) and solve for a vector in the nullspace.

* Matrix <img src="/tex/1e438235ef9ec72fc51ac5025516017c.svg?invert_in_darkmode&sanitize=true" align=middle width=12.60847334999999pt height=22.465723500000017pt/> is the reduced row echelon form (rref).  Use the pivots to clean
  up the rows above them and make pivots equal to 1. <img src="/tex/1e438235ef9ec72fc51ac5025516017c.svg?invert_in_darkmode&sanitize=true" align=middle width=12.60847334999999pt height=22.465723500000017pt/> for our above example
  is:

<p align="center"><img src="/tex/7959c9d92984071c0784524172664d9f.svg?invert_in_darkmode&sanitize=true" align=middle width=133.33354319999998pt height=59.1786591pt/></p>

* Note the identity matrix <img src="/tex/21fd4e8eecd6bdf1a4d3d6bd1fb8d733.svg?invert_in_darkmode&sanitize=true" align=middle width=8.515988249999989pt height=22.465723500000017pt/> is mixed into the rref matrix <img src="/tex/1e438235ef9ec72fc51ac5025516017c.svg?invert_in_darkmode&sanitize=true" align=middle width=12.60847334999999pt height=22.465723500000017pt/>.

* Typical rref looks like (I is identity matrix, F is free variables, the
  columns from I and F may be intermixed, <img src="/tex/89f2e0d2d24bcf44db73aab8fc03252c.svg?invert_in_darkmode&sanitize=true" align=middle width=7.87295519999999pt height=14.15524440000002pt/> pivot rows AND columns, <img src="/tex/6705abc37a8daba2b601e9e9771af618.svg?invert_in_darkmode&sanitize=true" align=middle width=42.397246649999985pt height=19.1781018pt/>
  free rows, <img src="/tex/bdc4fe24ac8ca702834e1744502f09d9.svg?invert_in_darkmode&sanitize=true" align=middle width=37.83102344999999pt height=19.1781018pt/> free columns):

<p align="center"><img src="/tex/10382425eb948366c69148d1b0ecdfac.svg?invert_in_darkmode&sanitize=true" align=middle width=71.5982586pt height=39.452455349999994pt/></p>

* Nullspace matrix (<img src="/tex/f9c4988898e7f532b9f826a75014ed3c.svg?invert_in_darkmode&sanitize=true" align=middle width=14.99998994999999pt height=22.465723500000017pt/>) - columns are the special solutions. <img src="/tex/942733788955d96b64cf2a3ee7984e69.svg?invert_in_darkmode&sanitize=true" align=middle width=57.74527934999999pt height=22.465723500000017pt/>.

<p align="center"><img src="/tex/c3408736ad0e11f3506d57d5defff14d.svg?invert_in_darkmode&sanitize=true" align=middle width=96.3469683pt height=39.452455349999994pt/></p>

* I find this part of the lecture confusing.  He is composing matrices (<img src="/tex/b8bc815b5e9d5177af01fd4d3d3c2f10.svg?invert_in_darkmode&sanitize=true" align=middle width=12.85392569999999pt height=22.465723500000017pt/> and
  <img src="/tex/21fd4e8eecd6bdf1a4d3d6bd1fb8d733.svg?invert_in_darkmode&sanitize=true" align=middle width=8.515988249999989pt height=22.465723500000017pt/>) that don't quite correspond to the example.

* Rank of <img src="/tex/99f7812af37ee7004df7177a1e821ec5.svg?invert_in_darkmode&sanitize=true" align=middle width=21.86251649999999pt height=27.6567522pt/> is the same as <img src="/tex/53d147e7f3fe6e47ee05b88b166bd3f6.svg?invert_in_darkmode&sanitize=true" align=middle width=12.32879834999999pt height=22.465723500000017pt/>.  <img src="/tex/f14f60eb1a566660335ef95423c1d84f.svg?invert_in_darkmode&sanitize=true" align=middle width=50.469792449999986pt height=27.6567522pt/> is dimension 1 in our example.

## [A tutorial on the free-energy framework for modelling perception and learning](https://www.sciencedirect.com/science/article/pii/S0022249615000759#bbr000050)
### Rafal Bogacz

* The predictive coding model provides a biologically-plausible account of how
  organisms infer stimuli from noisy inputs.  Introduced by Rao and Ballard in
  1999.  Friston extended the model in 2005 to also learn uncertainty
  associated with different features (e.g. attentional mechanism).  Friston's
  model can also be viewed as approximate Bayesian inference based on a
  minimization of free energy.

* This paper provides a tutorial that aims to be broadly accessible to a
  technical audience.

* Conditions for a model to be biological plausible:

    * Local computation - each neuron need only know about its inputs and
      outputs.

    * Local plasticity - localized changes can be used to train the model.

* We start with a problem: a single organism is trying to infer the diameter of
  a food item on the basis of observed light intensity from one noisy light
  receptor.  There exists a non-linear function `g` relating average light
  intensity with size.

* Interesting to note: once distributions aren't standard (e.g. normal or
  otherwise well known) you can't represent them compactly with summary
  statistics.  It seems likely there has to be some sort of approximation going
  on in the brain.

* Also interesting: calculating the bayesian normalization term (the
  denominator) seems difficult for neural systems (also, not super
  straightforward for computer systems, either).

* Suggests that instead of find the whole posterior, we just find the most
  likely size of the food item given the sensor reading.  This is claimed to be
  much more plausible to implement in neural circuits.

* Importantly, the value that maximizes the likelihood (phi) does not depend on
  the denominator so we can not consider it.  Take the natural log of the
  numerator `p(u | phi) * p(phi)` to get `ln(p(u | phi)) + ln(p(phi))`.


## [The free-energy principle: a unified brain theory?](https://www.fil.ion.ucl.ac.uk/~karl/The%20free-energy%20principle%20A%20unified%20brain%20theory.pdf)
### Karl Friston

* Biological systems aim to maintain homeostasis (i.e. they want to be in a
  limited set of physiological and sensory states).  Entropy is defined as the
  average surprise of outcomes sampled from a distribution.  Low entropy means
  that the outcome of a sampling is relatively predictable.  A biological
  system maintaining homeostasis is relatively low entropy in that there are a
  few states you will often be in and many states you will rarely be in.

* Biological agents aim to minimize the long-term average of surprise.

* The long-term imperative of maintaining states within physiological bounds
  translates into minimizing short-term surprise (note: seems like a greedy
  approach).

* Surprise is not just minimized in the state itself, but also in the movement
  between states.  This ends up resulting in states tending toward global
  random attractors (i.e. stable states that "self-correct" small random
  perturbations).

* Free energy is an upper bound on surprise.  While an agent can't directly
  minimize surprise, it can minimize free energy as free energy is a function
  on sensory states and recognition density.  Recognition density is a
  probabilistic representation of what causes a particular sensation.

* Agents can suppress free energy by acting on the world (change sensory input)
  and changing their internal state (change perception).

* Free energy minimization requires agents to have a generative model of the
  world.

* Discussion of Bayesian brain hypothesis: 1) hierarchy is important because it
  allows establishment of priors and 2) these priors are physically encoded in
  the brain (likely using a form of sufficient statistics e.g. the mean and
  stddev for a normal distribution).

* Bayesian brain ultimately views the brain as an inference engine that
  attempts to optimize probabilistic representations of what causes sensory
  input.  This view of the functioning of the brain can be derived from a
  free-energy approach.

* Stopped: principle of efficient coding section (p5)

* **Discussion**: surprise as -log(p).  entropy is the expected surpise.  For most
  processes, correctly modeling minimizes entropy but surprise will likely be
  irreducible.


## [Lecture 6: Column Space and Nullspace](https://ocw.mit.edu/courses/mathematics/18-06sc-linear-algebra-fall-2011/ax-b-and-the-four-subspaces/column-space-and-nullspace)
## Gilbert Strang

* Discussion of subspaces plane P through zero and line L through zero in
  R^3.  A bit confusing the exact definition of union and intersection, but
  if union is not a subspace in general (assuming L is not coplanar with P)
  while intersection is.

* Interestingly:  overdetermined equations (in this example, 3 unknowns and 4
  equations) don't fill the R^4 space so they can't always be solved.
  Overdetermined doesn't fill the subspace in this case.

* Column space :  all `b`'s that solve `Ax=b`.  In an `m`x`n` matrix, column
  space is a subspace R^m

* Null space: all `x`'s that solve `Ax=0`. In an `m`x`n` matrix, null space is
  a subspace of R^n

* Note that the solutions to `Ax=b` do not form a subspace in general for `b`
  (generally will not include the zero vector).  The nullspace is a vector
  space.

* Previewing the idea that you will have a particular solution to Ax=b, but
  then you can add a vector from the nullspace to also get another solution.

## [Surfing Uncertainty, Chapter 3: The Imaginarium](https://global.oup.com/academic/product/surfing-uncertainty-9780190217013)
### Andy Clark

* Evidence is presented that even early entrances to the brain (the V1 system)
  are deeply influenced by the constructive predictions coming top down (not
  just the bottom up senses).

* The VWFA area of the brain is activated during regular reading in normal
  subjects and braille reading in blind subjects.  Multimodal areas like this
  make sense in a hierarchical brain where top-down predictions drive
  perception.

* Our responses to missing stimuli (e.g. a song missing a particular beat) also
  suggest the use of generative models in the brain.  We habituate to sensory
  input, but then the removal of the input triggers a surprise response.

* Gives an example of listening to a familiar song through a bad radio.  You
  know the song but you can also focus attention and hear the bad quality of
  the radio (turn up the gain on the prediction error).

* Evidence that perception can occur faster to well-predicted stimuli.  Once
  the top-down model is in accord with the sensory input, perception occurs
  (and this happens faster with well-predicted stimuli).

* The generative nature of our top-down models can be repurposed for
  imagination (endogenous generation of sensory-like states). Perception
  co-emerges and is a dual of imagination.

* Reddy et al. experiment where brain signals were recorded as subjects viewed
  an image and as subjects imagined an image.  Classifiers were trained on both
  sets of data.  Classifiers were successful at picking out the images.
  Classifiers could also be swapped (i.e. the viewing classifier worked for the
  imagining data).  This suggests that the same pathways are activating by
  viewing and imagining.

* Evidence is presented that neurotransmitter balance determines how heavily we
  weight prediction error and thus how much of our modeling is constrained by
  sensory input vs in a hallucinating/dream state.

* Argument that sleep is used to regularize/prune overly complex and overfit
  generative models.

* PIMMS (predictive interactive multi-memory system): episodic (recalling
  specific times and place), semantic (knowing what something is), perceptual
  (recalling specific sensory percepts).


## [Introduction to Bayesian data analysis - Part 3: How to do Bayes?](https://www.youtube.com/watch?v=Ie-6H_r7I5A)
### Rasmus Bååth

* How to actual use Bayes in practice:  Approximate Bayesian computation (as
  we did in part 1 and 2) is slow.  Faster models all require that the
  generative model allows you to directly calculate the probability of seeing
  a particular result.  Faster models also explore the parameter space in a
  smarter way.

* relates Bayes to maximum likelihood estimation

* I find the model at time 5:30 a bit confusing.  My guess is that `y` is
  sampled from a normal distribution where the mean of the distribution is
  determined by `intercept + slope * x` and the stddev is held constant.  So,
  to generate a y, you select an x, plug it into the line equation to get the
  mean, and then sample for the normal with the determined mean (and chosen
  stddev).  Presumably, the sampling of the normal represents noise in the
  process.

* "Now this is a generative model, but it is not yet a Bayesian model.  For
  that, we need to represent all uncertainty by probability, and add prior
  distributions over all parameters.

* Result of Bayesian linear regression gives you an idea of how likely the
  various parameters are to have generated the data.

* TODO: find another explanation of a Bayesian approach to linear regression.

* Markov Chain Monte Carlo (MCMC) allows for exploration of complicated parameter
  spaces.  They walk around the parameter space and sample from the probability
  distributions.  They will revisit and sample each parameter set in proportion
  to how likely it is (to have generated the data).

* Stan is a language for Bayesian modelling.  You define your model in Stan and
  then it takes cares of fitting it.

* Things that can go wrong in MCMC: initial parameter values are way off, our
  algorithm doesn't have enough time to explore the parameter space, algorithm
  gets stuck at a local maximum.  Very similar to optimization.



## [Surfing Uncertainty, Chapter 2: Adjusting the Volume](https://global.oup.com/academic/product/surfing-uncertainty-9780190217013)
### Andy Clark


* How do you filter signal from noise and dynamically modify your filters?

* Sine wave speech priming perception - generative models playing a role in
  top-down processing.

* cognitive machinery continual estimates and re-estimates uncertainty in its
  predictions to decide how much to rely on sense vs top-down knowledge.

* On a foggy day, visual error is given less weight than on a bright and sunny
  day. Impact of prediction error is attenuated by the precision we expect from
  the sensory input.

* attention means we're putting higher value on the prediction error for the
  thing we're attending. There can be both an error enhancement and error
  suppression effect, depending on what we're attending.

* it seems hard to attend something for a long period where the attention does
  not generate new information.

* precision estimates on sensory data help us to balance and react to data
  better (e.g. in an environment where sight seems precise but audio not so
  much, we ignore some audio and rely more heavily on sight).

* the idea is introduced that the generative predictive models come with a
  game plan on how to best reduce uncertainty using your senses.

* Low level salience maps don't seem to describe our behavior in real
  situations; combinations of those with top-down predictive models do better
  (e.g. looking at where the ball will be in baseball).

* PP treats action, perception, and attention as forming a single mechanism for
  integrating bottom-up sensory data with top-down predictions.

* side note: thinking about magicians and how they manipulate our expectations
  on reducing uncertainty to perform their tricks.

* Active agents are driven to sample the world to confirm their own perceptual
  hypotheses.

* Confirmation bias directly falls out of this model

* schizophrenic hallucinations and delusions might represent a breakdown of the
  machinery that determines how reliable sensory data is and how reliable our
  predictions are.  False perceptions and bizarre beliefs can become
  self-reinforcing as hyperpriors are reshaped.

* From the wiki on [Predictive coding](https://en.wikipedia.org/wiki/Predictive_coding#General_framework):

    * A comparison between predictions (priors) and sensory input (likelihood)
      yields a difference measure (e.g. prediction error, free energy, or
      surprise) which, if it is sufficiently large beyond the levels of
      expected statistical noise, will cause the generative model to update so
      that it better predicts sensory input in the future.

    * If, instead, the model accurately predicts driving sensory signals,
      activity at higher levels cancels out activity at lower levels, and the
      posterior probability of the model is increased. Thus, predictive coding
      inverts the conventional view of perception as a mostly bottom-up
      process, suggesting that it is largely constrained by prior predictions,
      where signals from the external world only shape perception to the extent
      that they are propagated up the cortical hierarchy in the form of
      prediction error.


* Useful exercise: try to draw the Feynman machine like boxes proposed by
  predictive processing.

* **TODO**: find papers on implementation of predictive coding

## [Introduction to Bayesian data analysis - Part 2: Why use Bayes?](https://www.youtube.com/watch?v=mAUwjSo5TJE)
### Rasmus Bååth

This video illustrates how you might take a Bayesian approach to A/B testing.
The setup:

* We have our brochure experiment (method A) from before where 6 out of 16
  people signed up.
* We have a new experiment (brochure + sample, method B) where 10 out of 16
  people signed up.

We run the same algorithm from before to generate a posterior for method B.
Interestingly, you have to run the experiments in parallel and only keep the
results if both match (i.e. you draw a **p** from both priors, run the
simulation, and only keep the draws if both matched the observed data).  You
end up with a posterior distribution for both method A and method B.

What you also end up with is a set of rows where each row has two columns: the
chosen **p** for method A and the chosen **p** for method B that generated the
observed data. You can then add another processing step where you take the
difference between the two columns to get a third distribution and reason
about how likely it is that the true parameter for A is greater (or less than)
the true parameter for B.

Note, you can incorporate other information (e.g. expert opinion) in the
priors.  In the video, they model this using a beta distribution.  The
posterior ends up looking like a mix of the prior and the data.  The more data
you have, the more the posterior ends up looking like the data.

Bayesian analysis also retains the uncertainty around the estimated parameters
which can be useful for decision making. (Question: what if we're uncertain
about the generative model?).


## [Introduction to Bayesian data analysis - Part 1: What is Bayes?](https://www.youtube.com/watch?v=3OJEae7Qb_o)
### Rasmus Bååth

Key insight here is you can think of Bayes as requiring:

* Some data
* A generative model
* Priors

The motivating example was a fish-of-the-month club.  You run an experiment
where 6 out of 16 people (data) sign up after receiving a brochure.  You want
to get an estimate of the true sign-up rate.  You model the sign up choice as
a binomial with some unknown **p** (generative model) and you don't have a strong
thought on what the actual sign up rate is (uniform prior between 0% and
100%).

We will generate our posterior "guess" of the actual **p** as follows
(Approximate Bayesian Computation):

* Pick a **p** from the prior (uniform so p=.1 and p=.9 are equally likely to
  be selected)

* Plug the selected **p** into a binomial model, simulate the binomial with
  n=16 and p=**p**

* If the proportion of "successful" flips in the simulation equals the 6 we
  observed in the data, count the trial as a success.

* Repeat thousands of times.

What you end up with is a posterior distribution of the **p**'s most likely to
generate the 6 out of 16 you saw.  This looks normal around 37.5%.  This is
Bayes in a nutshell.  You take your prior, gather some evidence, and update
your prior into the posterior to incorporate your evidence.

**THOUGHTS**: very useful video series to generate some Bayesian intuition.


## [Surfing Uncertainty, Chapter 1: Prediction Machines](https://global.oup.com/academic/product/surfing-uncertainty-9780190217013)
### Andy Clark

Basically a high-level overview of the main contrast between the traditional
cognitive science depiction of perception vs his theory.

* Traditional: perception is a cumulative bottom-up process. you detect color
  and frequency, then edges, then curves, then combine that with stored
  knowledge and you perceive a coffee cup.

* Predictive Processing: perception is prediction.  Incoming sensory data is
  meshed with prediction, error signals propagate.  When the flow of prediction
  adequately accounts for the incoming sensory signals, the coffee cup is
  perceived.

Other notables from the chapter:

* He discusses the difficult task facing the brain; it sits in a dark box and
  all it has is a set of noisy sensors and it needs to make meaning from the
  signals of those sensors.  Bootstrapping seems tough!

* One of the benefits of the predictive processing paradigm: the situated state
  of cognition continually provides training data (you guess what's going to
  happen next, then the universe reveals the answer).

* Neural matter is incredibly dense.  An MNIST network can fit into .002 cubic
  mm of mouse cortex.

* The (comprehensible) universe is structured and compositional.  Hierarchy in
  the brains is used to perceive this structure.

* Hierarchical predictive coding: only the error signal ("surprisal") at each
  level is propagated up to a higher level.  This saves neural bandwidth.

* Perception actually occurs when our predictions align with our sensory data.

* Evidence is presented for "dynamic predictive coding" in retinal cells; the
  cells act to strip predictable elements from the visual stream so only the
  most noteworthy elements of the stream get forwarded up the hierarchy.

* Evidence is presented for bi-stable binocular rivalry.  If you show a subject
  two different images, one in each eye, they will generally alternate between
  perceiving one and the other.  When you perceive image 1, error is minimized
  for that image but high error is coming from image 2, so you change your
  prior and minimize the error for image 2 but this exacerbates image 1
  error. "Hyperpriors" are mentioned, priors that are deeply
  rooted/baked-in like the 2 different images can't both be occupying your
  visual field.

* Empirical bayes: your has priors, those priors get updated as evidence comes
  in to minimize error.  Perception is minimization of sensory prediction
  error.

* Predictive processing conceptualizes the forward flow as conveying error and
  the backward flow as conveying prediction that can "explain away" error.
  Thus it can both magnify or inhibit selectively.

* Evidence for the bayesian brain is presented.  A number of optical illusions
  can be recreated by using optimal Bayesian estimators.  Hollow mask illusion
  occurs in neurotypical people but less so in schizophrenics (perhaps
  suggesting schizophrenia is related to broken priors or prediction engines.)

* Predictive processing sees the brain as an active, generative thing
  ("proactive predictavores") rather than a passive recorder.

**THOUGHTS**: Good to read at a high-level and then fill in the picture with
targetted reviews.  A bit confused, are there both representational and error
neurons or is that all combined in the communication between layers.  Brains
are proactive predictavores.


## [Memory engrams: Recalling the past and imagining the future](https://science.sciencemag.org/content/367/6473/eaaw4325)
### Sheena Josselyn, Susumu Tonegawa

**Summary page only**

"Engram" is used to describe the neural substance of memories.  As we learn, we
generate persistent neural structures that can be reactivated due to related
stimuli. Evidence was initially scarce, but Hebbian learning (synaptic
connections strengthening/weakening based on stimulus) seemed promising.

Later experiments showed that destroying or activating specific neurons could
impede or aid memory retrieval.  Experiments also suggest that neurons
"compete" to be a part of memory, and this competition results in the larger
scale structure of the brain. Competition over excitability and neural
plasticity work hand-in-hand to create memory.  There is also a suggestion that
engrams can exist in different states (e.g. they can be unrecoverable, or
"silent").

Research is now ongoing to better understand and characterize these engrams.

**THOUGHTS**: the diagrams are approachable.  Easy to get lost in the details
of neurochemistry, might just be useful to read at a high-level and grapple
with the diagrams.


## [Surfing Uncertainty: Introduction](https://global.oup.com/academic/product/surfing-uncertainty-9780190217013)
### Andy Clark

The "trick" of how creatures learn and interact with the world, according to
the book, is guessing what the next sensory stimulation will be and using that
prediction error as a method to drive learning.  The prediction described here
is low-level and automatic, but occurs in hierarchical units that eventually
build up to higher level concepts that pull in symbolic knowledge (e.g. I
predict the cup will feel hot because I have a higher level model of coffee and
heat conduction).  We can learn about the world by attempting to generate
incoming sensory data for ourselves.  Actions are also a part of the loop, ways
that we can bring our predictions to fruition.  As we learn more about the
world, our predictions become more accurate.

This is closely related to the Bayesian brain hypothesis; that our brain
implements some approximation of Bayesian update to weigh new evidence and
judge what the likeliest scenario is.  Thus this model contains both prediction
mechanisms and mechanisms to estimate the reliability of those predictions.


## [Six views of embodied cognition](https://cogdev.sitehost.iu.edu/labwork/WilsonSixViewsofEmbodiedCog.pdf)
### Margaret Wilson

Overview of the notion that cognitive processes are deeply rooted in the body's
interaction with the world.  Specific claims examined:

* Cognition is situated - it takes place in a real world environment and is
  inherently contextual.

* Cognition is time pressured - the limits imposed by the real-time nature of
  cognition inherently shape the process.

* We offload cognitive work onto the environment - due to resource
  limitations, we offload cognition to the environment.

* The environment is part of the cognitive system - the link between mind and
  environment is so high-bandwidth that it doesn't make sense to study the mind
  separate from the environment (note: this claim is described as "deeply
  problematic" in the abstract).

* Cognition is for action - if cognition is for controlling our biological
  body, it must be understood in the context of performing actions.

* Offline cognition is body based - because the mind evolved contextually with
  the environment, even "abstract" thought hijacks sensorimotor facilities for
  cognition.

Notes there are (at least) two schools in the philosophy of mind/cognitive
sciences: the mind is an abstract information processor and sensorimotor
inputs/outputs are peripheral.  Alternatively, brains are control systems for
biological bodies and thus sensorimotor processing is intimately tied to
cognition.

A deeper examination of the claims:

#### Cognition is situated

A distinction is drawn between situated and unsituated cognition.  The former
is the cognition that happens as you do a task (e.g. hunting an animal), the
latter is the cognition that happens when you plan or daydream. These might be
variations on a theme (i.e. see the body-based cognition claim).

The author concludes that the argument that all important cognition is situated
(or rooted in situatedness) isn't strongly persuasive.  I feel a lot of this is
splitting hairs on definitions of particular technical terms.

#### Cognition is time pressured

This claim is, roughly, that the time pressure involved in situated cognition
is one of the primary shaping forces of cognition.  Brains evolved to, for
example, help us flee predators as they jump out of bushes and this deeply
influences how evolution shaped our cognitive processes.

Definition: representational bottleneck - time pressure causes a bottleneck
which forces us to rely on heuristic tricks

To temper this claim, a lot of what we identify as human cognition is not
aggressively time constrained.  For example, we do some of our best,
recognizably-human work when we can sit and reflect and plan.

It is noted that spatiotemporal and movement behaviors are probably deeply
influenced by time constraints.  However, the author is unpersuaded that this
can be "scaled up" and applied usefully to all of cognition.

#### We offload cognitive work to the environment

This is using the environment to work around real-time representational
bottlenecks.  This is distinct from offloading to prevent memorizing (e.g.
using a calendar) although they are sometimes conflated in the literature.

This, for example, could be moving furniture around a room to see how it looks
rather than trying to imagine how it would look.  This is also referred to as
"using the world as its own best model".

The author notes that it seems we use the environment for both time-pressured
situated tasks as well as unsituated tasks and that this may have far reaching
consequences for how we think about cognition.

#### The environment is part of the cognitive system

A stronger claim than previous; if we use the environment to offload
processing then the environment should always be considered a part of
cognition.

Alternatively, directly from the paper: "The claim is this: The forces that
drive cognitive activity do not reside solely inside the head of the
individual, but instead are distributed across the individual and the situation
as they interact. Therefore, to understand cognition we must study the
situation and the situated cognizer together as a single, unified system."

The author claims that causes of cognition are undeniably environmental and
internal, but that shouldn't necessarily constrain the examination of cognition
as a modular process.  The issue ends up being "how best to carve nature at its
joints" and depends deeply on what you're studying and what you're trying to
get out of the study.

The author gives the example of hydrogen from chemistry. Before there was a
theory of an atom, much was known about how hydrogen reacts in many different
situations.  As atomic theory was developed though, so was a useful
understanding of hydrogen as something unto itself.  Both lines of research
were fertile.

#### Cognition is for action

The proposal here is that memory shouldn't be viewed as a tool for recording
abstract information, but rather a tool for encoding patterns of possible
action in a 4D world.

This claim is tempered by the fact that we remember things that we cannot
directly interact with (e.g. sunsets are mentioned, even though we do look at
them).  More broadly, there is suggestion that there different types of memory.
Some are more closely coupled with action and others are more abstract.

The other tempering fact is that it seems we often build up richer
representation of objects beyond the here-and-now usefulness. For example, the
piano that is a musical instrument that becomes firewood once the blizzard
strikes.  The representations allow us to be creative when the environment
changes.

#### Offline cognition is body based

The claim is that we hijack our sensorimotor tools to do other, higher-levels
of cognition. Examples include mental imagery, different types of
sensory-linked working memory, episodic memories, etc.

Excerpts from the paper's conclusion:

* "One benefit of greater specificity [of the claims around embodied cognition]
  is the ability to distinguish on-line aspects of embodied cognition from
  off-line aspects."

* In online, situated cases of cognition, "the mind can be seen as operating to
  serve the needs of a body interacting with a real-world situation."  Issues
  of time pressure may come into play.  We should be careful, however, in
  scaling up the processes that come into play to explain all of cognition.


* In offline, unsituated forms of cognition, "rather than the mind operating to
  serve the body, we find the body (or its control systems) serving the mind.
  This takeover by the mind, and the concomitant ability to mentally represent
  what is distant in time or space, may have been one of the driving forces
  behind the runaway train of human intelligence that separated us from other
  hominids."

**THOUGHTS**: a decent survey of the field, gives good high-level pointers.
Sometimes a little overly-hair-splitting when it comes to definitions.


## [Schema Networks: Zero-shot Transfer with a Generative Causal Model of Intuitive Physics](https://arxiv.org/abs/1706.04317)
### Ken Kansky, Tom Silver, David A. Mély, Mohamed Eldawy, Miguel Lázaro-Gredilla, Xinghua Lou, Nimrod Dorfman, Szymon Sidor, Scott Phoenix, Dileep George

Examines transfer learning using the game of Breakout as an example.  Current
state-of-the-art RL techniques can learn to play Breakout very well.  However,
minor modifications to the game rules (e.g. changing size or shape of paddle,
changing how the bricks react) to which humans can easily adapt will break
deep neural net based agents.

Techniques like model-free DQN make no assumption about the domain. This makes
it useful for one off tasks but it can overfit the particulars of the domain
and limit its ability to generalize to closely related (in human terms)
domains.  Object-based and relational representations have been explored to
address this limitation.  This paper throws causality into the mix by
introducing Schema Networks – a generative model for object-oriented
reinforcement learning and planning.

* NOTE: they mention reasoning backward from an objective in order to plan.
  Very similar to one of the heuristics in the RAND paper.

* NOTE: might want to explore more from the related work section

The basics of their model is that there are **entities** (e.g. objects parsed from
an image input), each of these entities have **attributes** and each of the
attributes have a value.  Then there are **schemas** which capture the relationship
between entities, entity attributes, actions, and rewards over time. An example
of this is Entity 1's position attribute at timestep 5 may be predicated on
Entity 1's position attribute at timestep 4 and taking the "UP" action.

They distinguish between **ungrounded schema** and **grounded schema**. An
ungrounded schema is a template that expresses a relationship (e.g. action "UP"
on an entity will increase its position attribute), and a grounded schema is a
particular instantiation of an ungrounded (e.g. action "UP" on Entity 1 will
increase its position attribute to 5).

They then extend the standard MDP formalism so that a given state simply
consists of the set of all entities and their particular attribute values.
Then schemas can be placed upon all the attributes in the entities in a given
state to predict their next values.  Each schema is a set of AND'd
preconditions.  And each attribute value can be predicted by multiple schema
OR'd together.  The OR-ing of multiple schemas allow explicit reasoning about
multiple causation.

* TODO: lookup object-oriented MDPs and relational MDPs

Now, we must figure out how to **learn** a schema network and then use it for
**planning**.

There is some magic pre-processing that picks out entities.  Then they
represent the current state using a neighbor-based algorithm (seemingly to
capture entities which are nearby each other).  They use epsilon-greedy
exploration algorithm.

To learn the structure of the Schema Network, they "cast the problem as a
supervised learning problem over a discrete space of parameterizations (the
schemas),  and then apply a greedy algorithm that solves a sequence of LP
relaxations."  This seems like a probably-well-understood method of learning.
A key balance they're trying to strike is to both minimize prediction error
WHILE minimizing the complexity of the schema network.  The general problem is
NP-hard, so they use a greedy approximation method to generate a solution.

Once they learn a Schema Network, they then use it for planning to get to a
desired state (e.g. collect positive rewards, avoid negative rewards). They do
this by (roughly):

* Working forward in their model for T time steps to figure out reachable
  states.
* Choosing the reachable state with the best reward.
* Backtracking to confirm its the chosen state's reachability and discover the
  set of actions that will maximize the chance of reaching that state.

They then compare Schema Networks to A3C and Progressive Networks (PNs) on
several variations of Breakout.  They show that Schema Networks transfer their
learning much faster than A3C or PNs to different variants of Breakout.  They
then show that Schema Networks can adapt to variants of the game (that exhibit
the same dynamics) much better than A3C or PNs (e.g. when paddle is offset by N
pixels) in a zero-shot setting (i.e. train only on regular breakout and then
have it play the variant).

From the conclusion: "Instead of learning policies to maximize rewards, the
learning objective for Schema Networks is designed to understand causality
within these environments.  The fact that Schema Networks are able to achieve
rewards more efficiently than state-of-the-art model-free methods like A3C is
all the more notable, since high scores are a byproduct of learning an accurate
model of the game."

**THOUGHTS:** Interesting whirlwind tour of the PGM world and how one might try
to learn higher-level models.  Don't have enough background to evaluate how
novel or effective this particular technique is, but seems promising from their
results. A lot of pointers to work worth following up on (e.g. OO-MDPs, PGMs in
general, MAP/MBPB, planning, etc)


## [Feynman Machine: The Universal Dynamical Systems Computer](https://arxiv.org/abs/1609.03971)
### Eric Laukien, Richard Crowder, Fergal Byrne

Introduce Feynman Machines, a universal computer paradigms for dynamical
systems (vs Turing machines, a universal computer for symbolic systems).  Claim
that hierarchies of interacting dynamical systems closely resemble what's going
on in the mammalian context.

* TODO: Theorem of Floris Takens - models derived from time series signals are
  essentially true analogues of the system producing the signals.

Science is the study of things that change over time, a search for rules and
laws which describe their structure and evolution over time, and is based on
the premise that the world is lawful and its rules are discoverable.

* Dynamical system -- a system governed by express update rules (either
  continuous or discrete)

* Lorenz atmospheric convection model - an example of a dynamical system (3
  coupled differential equations) that exhibits deterministic chaos; the
  further out in the future you want to predict the state, the more precise
  your initial measurements of the system must be.

* Takens theorem - a model constructed from a time series is fundamentally
  the same as the system being observed (diffeomorphic).

Feynman Machine is divided into regions.  Each region has a visible/downward
and an hidden/upward face.  Each face has inputs and outputs.

* visible/downward input - sensorimotor data from lower regions

* visible/downward output - predictions of future inputs (alternatively,
  control/behavior/feedback/routing signals)

* hidden/upward input - receives predictions of future inputs from higher
  regions

* hidden/upward output - encodings of the sensorimotor data received from the
  visible input

Each region is wired up with internal recurrent channels.  Hidden output is
combined with hidden input to generate the visible output.  This is compared
with the visible input and the error is used to drive learning.

In implementation, this looks like a hierarchy of paired encoders and decoders
(predictors).  Each one attempts to predict the state of the predictors below
it one time step in advance.  This drives learning.

They then go into detail about the specific encoder/decoder they implement
(Spatiotemporal K-sparse autoencoder) and discuss several benchmarks that
they've gotten good results on with lower compute requirements.

* TODO - Friston on free energy
* TODO - Jeff Hawkins, On Intelligence and follow-on work
* TODO - Autoencoders
* TODO - AIXI model

**THOUGHTS:** This reads a lot like a white paper.  We would be interested in
more details of their evaluation. Still intriguing, and harmonizes with a lot
of what is coming out of the neuroscience world (e.g see Clark's Surfing
Uncertainty), esp. because we found them because they were getting interesting
results training and running on a Raspberry Pi.

## [Neural Networks are Surprisingly Modular](https://arxiv.org/abs/2003.04881)
### Daniel Filan, Shlomi Hod, Cody Wild, Andrew Critch, Stuart Russell

A look at the modularity of neural networks.  They develop a notion of
modularity.  Specifically, modules in neural nets are groups of neurons that
are highly connected internally and weakly connected externally.

First experiment is to train a network on a classification task, and then try
to cluster modules.  Then they reshuffle the weights of the network and again
re-cluster.  They find that the generally trained networks are more modular than
the randomly shuffled ones. Interestingly, though, CIFAR is not very modular by
this metric (i.e. the trained network tends to be LESS modular than the
shuffled one).

They then try this experiment with dropout.  Dropout makes the networks much
more modular.

They then examine whether this modularity is a result of the optimization
algorithm (ADAM).  They show that running ADAM on an unlearnable dataset does
not result in a particularly modular network (although they had some outliers
on some of the longer training runs that were very modular).

Similarly, they tried to memorize a small, random noise dataset.  They show
that generally the networks that memorize the data are more clusterable
(although dropout seems to prevent this but also does not learn the data).

They then do lesioning experiments where they "kill" certain modules.  They
show that some of these modules end up being highly impactful in the
classification accuracy of the network.


## [Zoom In: An Introduction to Circuits](https://distill.pub/2020/circuits/zoom-in/)
### Chris Olah, Nick Cammarata, Ludwig Schubert, Gabriel Goh, Michael Petrov, Shan Carter

Makes three speculative claims about the understandability of neural networks:

* Features - Features are the fundamental unit of neural networks (e.g. curve detectors).
* Circuits -  Features are connected by weights, forming circuits. A “circuit”
  is a computational subgraph of a neural network. It consists of a set of
  features, and the weighted edges that go between them in the original
  network.
* Universality - Analogous features and circuits form across models and tasks.

They claim all these can be examined manually and often understood.  One
interesting technique is they implement a curve detector feature by hand in a
neural net.

Also, however, note that neural networks often contain “polysemantic neurons”
that respond to multiple unrelated inputs. For example, InceptionV1 contains
one neuron that responds to cat faces, fronts of cars, and cat legs.

Features build up into circuits.  They dig into a dog head detector that's
built up of smaller curve detectors and snout detectors and various connections
(both excitatory and inhibitory) between them.

They then highlight a case of superposition: a bunch of features feed into a
singular "car detector" neuron but then that neuron gets redistributed to a
bunch of other polysemantic neurons that detect dogs and cars.  From the
article: "Why would it do such a thing? We believe superposition allows the
model to use fewer neurons, conserving them for more important tasks. As long
as cars and dogs don’t co-occur, the model can accurately retrieve the dog
feature in a later layer, allowing it to store the feature without dedicating a
neuron".

They then discuss anecdotal evidence for universality--that there are some
features that re-appear again and again in neural nets (e.g. edge detection).
Strong universality might guide the nature of future interpretability  research.

**TODO** in the glossary there are a bunch of related articles that seem useful,
including:

* [Feature Visualization (2017)](https://distill.pub/2017/feature-visualization/)
* [The Building Blocks of Interpretability (2018)](https://distill.pub/2018/building-blocks/)
* [Exploring Neural Networks with Activation Atlases (2019)](https://distill.pub/2019/activation-atlas/)
