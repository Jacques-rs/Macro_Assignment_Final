# Introduction

According to Belongia and Ireland (2020), nominal interest rate
management has been the Federal Reserve’s approach to stabilize the
output gap and inflation. The Taylor Rule is a good predictor of the
nominal interest rate management. Interest rate management has been
endorsed by literature and has shown advantages over the management of
money stock, however, economists have only argued against a constant
monetary growth rule but have neglected the potential benefits of a
potential benefits of a flexible monetary growth rule. The Belongia and
Ireland (2020) paper is a reconsideration of money growth rules in an
estimated New Keynesian model.In this paper, the New Keynesian model by
Belongia and Ireland (2020) is replicated. Firstly, the model is
explained. The first order conditions log-linearisations are then
presented.

# The Model

In this paper, the model economy consists of a representative household,
a representative finished goods-producing firm, a continuunm of
intermediate goods-producing firms (indexed by *i* ∈ \[0;1\]) and a
central bank. During each period, each intermediate goods-producing firm
produces a distinct intermediate good. As such, intermediate goods are
also indexed by *i* ∈ \[0;1\], with good *i* produced by firm *i*. The
model features enough symmetry, however, to allow the analysis to focus
on the behavior of a representative intermediate goods-producing firm
that manufactures the generic intermediate good *i*. Habit formation
introduced through the representative household’s preferences and
incomplete indexation of sticky nominal goods prices set by
monopolistically competitive intermediate goods-producing firms imply
that the model’s New Keynesian IS and Phillips curves include both
backward and forward-looking elements. The estimation procedure allows
the data to decide on the relative importance of these backward and
forward-looking terms. The central bank in the estimated model is
assumed to conduct monetary policy according to a version of the Taylor
(1993) rule, the standard New Keynesian representation of the Federal
Reserve’s actual practice of federal funds rate targeting over most if
not all of the 1983-2019 sample period. As noted above, however, the
introduction of a money demand curve of a form that is consistent with
the same US data also permits consideration of counterfactual monetary
policy rules for money growth targeting instead.

# Derivations of Model’s First Order Conditions:

## The Representative Household

The representative household enters each period *t* = 0, 1, 2, ... with
*M*<sub>*t* − 1</sub> units of money and *B*<sub>*t* − 1</sub> bonds. At
the beginning of period *t*, the household receives a lump-sum monetary
transfer *T*<sub>*t*</sub> from the central bank. In addition, the
household’s bonds mature, yielding *B*<sub>*t* − 1</sub> additional
units of money. The household uses some of this money to purchase
*B*<sub>*t*</sub> new bonds at the price of 1 = *r**t* units of money
per bond; thus, *r*<sub>*t*</sub> denotes the gross nominal interest
rate between *t* and *t* + 1. During period *t*, the household supplies
*h*<sub>*t*</sub>(*i*) units of labour to each intermediate
goods-producing firm *i* ∈ \[0;1\]. The household gets paid at the
nominal wage rate *W*<sub>*t*</sub>, earning
*W*<sub>*t*</sub>*h*<sub>*t*</sub> in labour income, where

*h*<sub>*t*</sub> = ∫*h*<sub>*t*</sub>(*i*) *d**i*

denotes total hours worked during the period. Also during period *t*,
the household consumes *C*<sub>*t*</sub> units of the finished good,
purchased at the nominal price *P*<sub>*t*</sub> from the representative
finished goods-producing firm. At the end of period *t*, the household
receives nominal profits *D*<sub>*t*</sub>(*i*) from each intermediate
goods-producing firm *i* ∈ \[0;1\]. The household then carries
*M*<sub>*t*</sub> units of money into period *t* + 1, chosen subject to
the budget constraint

$$\\frac{M\_{t-1}+T\_{t}+B\_{t-1}+W\_{t}h\_{t}+D\_{t}}{P\_{t}} \\ge C\_{t} + \\frac{M\_{t} + \\frac{B\_{t}}{r\_{t}}}{P\_{t}}$$

for all *t* = 0, 1, 2, ..., where

*D*<sub>*t*</sub> = ∫<sub>0</sub><sup>1</sup>*D*<sub>*t*</sub>(*i*) *d**i*

denotes total profits received for the period. The household’s
preferences are described by the expected utility function

$$E\_{0}\\sum\_{t=0}^{\\infty}\\beta^{t}a\_{t}\[ln(C\_{t} - \\gamma C\_{t-1}) + v(\\frac{M\_{t}}{P\_{t}Z\_{t}}, u\_t)-(\\frac{\\phi\_m}{2})(\\frac{M\_t/P\_t}{zM\_{t-1}/P\_{t-1}}-1)^{2}(\\frac{M\_{t}}{P\_{t}Z\_{t}})-h\_{t}\]$$

where both the discount factor and the habit formation parameter lie
between zero and one, with 0 &lt; *β* &lt; 1 and 0 ≥ *γ* ≤ 1. The
preference shock *a*<sub>*t*</sub> follows the stationary autoregressive
process:

ln (*a*<sub>*t*</sub>) = *ρ*<sub>*a*</sub>ln (*a*<sub>*t* − 1</sub>) + *ε*<sub>*a**t*</sub>

for all *t* = 0, 1, 2, ..., with 0 ≥ *ρ*<sub>*a*</sub> ≤ 1, where the
serially uncorrelated innovation *ε*<sub>*a**t*</sub> is normally
distributed with mean zero and standard deviation *σ*<sub>*a*</sub>.
Utility is additively separable across consumption, real balances, and
hours worked so as to imply a specifcation for the model’s IS curve that
does not include terms involving money and employment.As shown by King,
Plosser, and Rebelo (1988), additive separability also implies that a
logarithmic specifcation over consumption is needed for the model to be
consistent with balanced growth. Also for balanced growth, real balances
*M*<sub>*t*</sub> = *P*<sub>*t*</sub> enter utility through the function
*v* after being scaled by the aggregate productivity shock
*Z*<sub>*t*</sub>, which follows a random walk with drift:

ln (*Z*<sub>*t*</sub>) = ln *z* + ln (*Z*<sub>*t* − 1</sub>) + *ε*<sub>*z**t*</sub>

where the serially uncorrelated error term or innovation is normally
distributed with zero mean and standard deviation *σ*<sub>*z*</sub>. The
shock *u*<sub>*t*</sub> to money demand follows the stationary
autoregressive process:

ln (*u*<sub>*t*</sub>) = *ρ*<sub>*u*</sub>ln (*u*<sub>*t* − 1</sub>) + *ε*<sub>*u**t*</sub>
for all *t* = 0, 1, 2, ... with 0 ≥ *ρ*<sub>*u*</sub> &lt; 1, where the
serially uncorrelated innovation *ε*<sub>*u**t*</sub> is normally
distributed with mean zero and standard deviation *σ*<sub>*u*</sub>.
Finally, the parameter *ϕ*<sub>*m*</sub> ≥ 0 governs the magnitude of
the adjustment cost for real balances, adapted from Nelson (2002) and
Andres, Lopez-Salido, and Nelson (2004, 2009) to take the quadratic
functional form used here. Since these costs subtract from utility along
with hours worked, they have the interpretation as a time cost, and are
scaled by the average growth rate parameter *z* from (3) so as to equal
zero in the model’s steady state. Thus, the household chooses
*C**t*, *h**t*, *B**t*, and *M**t* for all *t* = 0, 1, 2, ..., to
maximize expected utility subject to the budget constraint (1) for all
*t* = 0, 1, 2, ...,

### First Order Conditions

The Lagrangian for the consumer can be described by the following, given
the household constraint:

$$E\_{0} \\sum\_{t=0}^\\infty \\beta^ta\_t\[\\ln(C\_{t}-\\gamma C\_{t-1})+v(\\frac{M\_t}{P\_tZ\_t},u\_t)-\\frac{\\phi\_m}{2}(\\frac{\\frac{M\_t}{P\_t}}{\\frac{zM\_{t-1}}{P\_{t-1}}}-1)^2(\\frac{M\_t}{P\_tZ\_t})-h\_t\]$$
$$+ E\_0 \\sum\_{t=0}^\\infty \\Lambda\_t\[\\frac{M\_{t-1} + T\_t +B\_{t-1} + W\_th\_t+D\_t}{P\_t}-C\_t- (\\frac{M\_t+\\frac{B\_t}{r\_t}}{P\_t})\]$$

#### The FOC with respect to *C*<sub>*t*</sub>:

$$\\frac{\\partial L(C\_t, h\_t, B\_t, M\_t)}{\\partial C\_t}= \\beta^t a\_t(\\frac{1}{C\_t-\\gamma C\_{t-1}})-\\beta^t\\Lambda\_t + E\_t\\beta^{t+1}a\_{t+1}(-\\gamma)(\\frac{1}{C\_{t+1}-\\gamma C\_t})$$

Equate to zero and solve:

$$0= \\beta^t a\_t(\\frac{1}{C\_t-\\gamma C\_{t-1}})-\\beta^t\\Lambda\_t + E\_t\\beta^{t+1}a\_{t+1}(-\\gamma)(\\frac{1}{C\_{t+1}-\\gamma C\_t})$$

$$\\beta^t\\Lambda\_t = \\beta^t a\_t(\\frac{1}{C\_t-\\gamma C\_{t-1}}) + E\_t\\beta^{t+1}a\_{t+1}(-\\gamma)(\\frac{1}{C\_{t+1}-\\gamma C\_t})$$

#### The FOC with respect to *h*<sub>*t*</sub>:

$$\\frac{\\partial L(C\_t, h\_t, B\_t, M\_t)}{\\partial h\_t}= (-1)(\\beta^t a\_t) + (\\frac{W\_t}{P\_t})(\\beta^t\\Lambda\_t)$$

Equate to zero and solve:

$$0 = (-1)(\\beta^t a\_t) + (\\frac{W\_t}{P\_t})(\\beta^t\\Lambda\_t)$$
$$(\\beta^t a\_t) = (\\frac{W\_t}{P\_t})(\\beta^t\\Lambda\_t) $$
$$ a\_t = (\\frac{W\_t}{P\_t})(\\Lambda\_t) $$

#### The FOC with respect to *B*<sub>*t*</sub>:

$$\\frac{\\partial L(C\_t, h\_t, B\_t, M\_t)}{\\partial B\_t}= (\\frac{-1}{r\_t P\_t})(\\beta^t\\Lambda\_t) + E\_t\\beta^{t+1}\\Lambda\_{t+1}(\\frac{1}{P\_{t+1}})$$

Equate to zero and solve:

$$ 0=(\\frac{-1}{r\_t P\_t})(\\beta^t\\Lambda\_t) + E\_t\\beta^{t+1}\\Lambda\_{t+1}(\\frac{1}{P\_{t+1}})$$
$$ (\\frac{1}{r\_t P\_t})(\\beta^t\\Lambda\_t) = E\_t\\beta^{t+1}\\Lambda\_{t+1}(\\frac{1}{P\_{t+1}})$$
$$ \\beta^t\\Lambda\_t = (r\_t P\_t) E\_t\\beta^{t+1}\\Lambda\_{t+1}(\\frac{1}{P\_{t+1}})$$
$$ \\Lambda\_t = \\beta(r\_t) E\_t(\\frac{P\_t\\Lambda\_{t+1}}{P\_{t+1}})$$

Because:
$$\\pi\_t=\\frac{P\_t}{P\_{t-1}}$$

Therefore:
$$\\frac{P\_t}{P\_{t+1}}=\\frac{1}{\\pi\_{t+1}}$$

As such, the equation can be rewritten as:

$$\\Lambda\_t = \\beta(r\_t)E\_t(\\frac{\\Lambda\_{t+1}}{\\pi\_{t+1}})$$

#### The FOC with respect to *M*<sub>*t*</sub>:

$$\\frac{\\partial L(C\_t, h\_t, B\_t, M\_t)}{\\partial M\_t}=\\beta^ta\_t\[v(\\frac{1}{P\_tZ\_t})-\\phi\_m(\\frac{\\frac{M\_t}{P\_t}}{\\frac{z\_tM\_{t-1}}{P\_{t-1}}}-1)(\\frac{P\_{t-1}}{ZM\_{t-1}P\_t})(\\frac{M\_t}{P\_tZ\_t})-\\frac{\\phi\_m}{2}(\\frac{\\frac{M\_t}{P\_t}}{\\frac{z\_tM\_{t-1}}{P\_{t-1}}}-1)^2(\\frac{1}{P\_tZ\_t})\]+\\beta\\Lambda\_t\[-\\frac{1}{P\_t}\]+$$
$$E\_t\\beta^{t+1}a\_{t+1}\[-\\phi\_m(\\frac{M\_{t+1}/P\_{t+1}}{ZM\_t/Pt}-1)(-\\frac{M\_t/P\_t}{ZM\_{t-1}^2/P\_{t-1}})(\\frac{M\_t}{P\_tZ\_t})\]+E\_t\\beta^{t+1}\\Lambda\_{t+1}(\\frac{1}{P\_t})$$

Equate to zero and solve:

$$\\beta^ta\_t\[v(\\frac{1}{P\_tZ\_t})-\\phi\_m(\\frac{\\frac{M\_t}{P\_t}}{\\frac{z\_tM\_{t-1}}{P\_{t-1}}}-1)(\\frac{P\_{t-1}}{ZM\_{t-1}P\_t})(\\frac{M\_t}{P\_tZ\_t})-\\frac{\\phi\_m}{2}(\\frac{\\frac{M\_t}{P\_t}}{\\frac{z\_tM\_{t-1}}{P\_{t-1}}}-1)^2(\\frac{1}{P\_tZ\_t})\]+\\beta\\Lambda\_t\[-\\frac{1}{P\_t}\]+$$
$$E\_t\\beta^{t+1}a\_{t+1}\[-\\phi\_m(\\frac{M\_{t+1}/P\_{t+1}}{ZM\_t/Pt}-1)(-\\frac{M\_t/P\_t}{ZM\_{t-1}^2/P\_{t-1}})(\\frac{M\_t}{P\_tZ\_t})\]+E\_t\\beta^{t+1}\\Lambda\_{t+1}(\\frac{1}{P\_t}) = 0$$
$$v\_t(\\frac{M\_t}{P\_tZ\_t},u\_t) = \\frac{1}{\\delta}\[\\ln(m\*) - \\ln(\\frac{M\_t}{P\_tZ\_t}) + \\ln(u\_t)\]$$

## The Representative Finished Goods-Producing Firm

The representative finished goods-producing firm uses
*Y*<sub>*t*</sub>(*i*) units of each intermediate good *i* ∈ \[0,1\].
These intermediate goods are bought at the nominal price
*P*<sub>*t*</sub>(*i*) in order to produce *Y*<sub>*t*</sub> units of
the final good according to the technology described by

$$\[\\int\_0^1Y\_t(i)^{\\frac{(\\theta\_t-1)}{\\theta\_t}} di\]^{\\frac{\\theta\_t}{\\theta\_t-1}} \\ge Y\_t$$

where *θ*<sub>*t*</sub> translates into a random shock to the
intermediate goods-producing firms’ desired markup of price over
marginal cost and therefore acts like a cost push shock of the kind
introduced into the New Keynesian model by Clarida, Gali, and and
Gertler (1999). Here, this markup shock follows the stationary
autoregressive process

ln (*θ*<sub>*t*</sub>) = (1−*ρ*<sub>*θ*</sub>)ln (*θ*) + *ρ*<sub>*θ*</sub>ln (*θ*<sub>*t* − 1</sub>) + *ε*<sub>*θ**t*</sub>

for all *t* = 0, 1, 2, ...,, where the serially uncorrelated innovation
*ε*<sub>*θ**t*</sub> is normally distributed with mean zero and standard
deviation *σ*<sub>*θ*</sub>. Thus, during each period *t*, the finished
good-producing firm chooses *Y*<sub>*t*</sub>(*i*) for all *i* ∈ \[0,1\]
to maximize its profits, which are given by

$$P\_t\[\\int\_0^1Y\_t(i)^{\\frac{\\theta\_t-1}{\\theta\_t}} di\]^{\\frac{\\theta\_t}{\\theta\_t-1}} - \\int\_0^1P\_t(i)Y\_t(i) \\;di$$

The Langrangian function from which the first order conditions are
derived, is as follows:

$$L = \\int\_0^1P\_t(i)Y\_t(i) \\; di +\\lambda\_t\[Y\_t - (\\int\_0^1Y\_t(i)^{\\frac{\\theta\_t-1}{\\theta\_t}} \\;di)^{\\frac{\\theta\_t}{\\theta\_t-1}}\]$$

#### The FOC with respect to *Y*<sub>*t*</sub>(*i*):

$$\\frac{\\partial L}{\\partial Y\_t(i)} = P\_t(i) - \\lambda\_t\[{\\frac{\\theta\_t}{\\theta\_t-1}} (\\int\_0^1 Y\_t(i)^{\\frac{\\theta\_t-1}{\\theta\_t}} di)^{\\frac{\\theta\_t}{\\theta\_t-1} -1} \\frac{\\theta\_t-1}{\\theta\_t} Y\_t(i)^{\\frac{\\theta\_t-1}{\\theta\_t} -1}\] = 0$$
$$P\_t(i) - \\lambda\_t\[{\\frac{\\theta\_t}{\\theta\_t-1}} (\\int\_0^1 Y\_t(i)^{\\frac{\\theta\_t-1}{\\theta\_t}} di)^{\\frac{1}{\\theta\_t-1}} \\frac{\\theta\_t-1}{\\theta\_t} Y\_t(i)^{\\frac{-1}{\\theta\_t}}\] = 0$$

$$ \\lambda\_t\[\\int\_0^1 Y\_t(i)^{\\frac{\\theta\_t-1}{\\theta\_t}} di\]^{\\frac{1}{\\theta\_t-1}} Y\_t(i)^{\\frac{-1}{\\theta\_t}} = P\_t(i)$$

$$ \\lambda\_t\[\\int\_0^1 Y\_t(i)^{\\frac{\\theta\_t-1}{\\theta\_t}} di\]^{\\frac{1}{\\theta\_t-1}}  = P\_t(i)Y\_t(i)^{\\frac{1}{\\theta\_t}}$$
$$ \\lambda\_t\[\\int\_0^1 Y\_t(i)^{\\frac{\\theta\_t-1}{\\theta\_t}} di\]^{\\frac{1}{\\theta\_t-1}}P\_t(i)^{-1}  = Y\_t(i)^{\\frac{1}{\\theta\_t}}$$

$$ \\lambda\_t^{\\theta\_t} \[\\int\_0^1 Y\_t(i)^{\\frac{\\theta\_t-1}{\\theta\_t}} di\]^{\\frac{\\theta\_t}{\\theta\_t-1}}P\_t(i)^{-\\theta\_t}  = Y\_t(i)$$

*λ*<sub>*t*</sub><sup>*θ*<sub>*t*</sub></sup>*Y*<sub>*t*</sub>*P*<sub>*t*</sub>(*i*)<sup>−*θ*<sub>*t*</sub></sup> = *Y*<sub>*t*</sub>(*i*)
Where
$Y\_t = \[\\int\_0^1 Y\_t(i)^{\\frac{\\theta\_t-1}{\\theta\_t}} di\]^{\\frac{\\theta\_t}{\\theta\_t-1}}$

$$ (\\frac{\\lambda\_t}{P\_t(i)})^{\\theta\_t} Y\_t  = Y\_t(i)$$
Sub $Y\_t(i) = (\\frac{\\lambda\_t}{P\_t(i)})^{\\theta\_t} Y\_t$ into
*Y*<sub>*t*</sub>

$$\[\\int\_0^1 ((\\frac{\\lambda\_t}{P\_t(i)})^{\\theta\_t} Y\_t)^{\\frac{\\theta\_t-1}{\\theta\_t}} di\]^{\\frac{\\theta\_t}{\\theta\_t-1}}  = Y\_t$$
$$\[\\int\_0^1 ((\\frac{P\_t(i)}{\\lambda\_t})^{-\\theta\_t})^{\\frac{\\theta\_t-1}{\\theta\_t}} di\]^{\\frac{\\theta\_t}{\\theta\_t-1}}  = 1$$
$$(\\frac{1}{\\lambda\_t})^{-\\theta\_t}\[\\int\_0^1 (P\_t(i))^{-\\theta\_t+1} di\]^{\\frac{\\theta\_t}{\\theta\_t-1}}  = 1$$

$$\[\\int\_0^1 (P\_t(i))^{1-\\theta\_t} di\]^{\\frac{\\theta\_t}{\\theta\_t-1}}  = {\\lambda\_t}^{-\\theta\_t}$$
$$\[\\int\_0^1 (P\_t(i))^{1-\\theta\_t} di\]^{\\frac{1}{1-\\theta\_t}}  = {\\lambda\_t}$$
Therefore:

*λ*<sub>*t*</sub> = *P*<sub>*t*</sub>
Sub *Y*<sub>*t*</sub> = *P*<sub>*t*</sub> back in:

$$(\\frac{P\_t}{P\_t(i)})^{\\theta\_t} Y\_t = Y\_t(i)$$
Therefore:

$$Y\_t(i) = (\\frac{P\_t(i)}{P\_t})^{-\\theta\_t} Y\_t$$

## The Representative Intermediate Goods-Producing Firm

During each period *t* = 0, 1, 2, ..., the representative intermediate
goods-producing firm hires *h*<sub>*t*</sub>(*i*) units of labour from
the representative household to manufacture *Y*<sub>*t*</sub>(*i*) units
of intermediate good *i* according to the technology described by:

*Z*<sub>*t*</sub>*h*<sub>*t*</sub>(*i*) ≥ *Y*<sub>*t*</sub>(*i*)
where *Z*<sub>*t*</sub> is the aggregate productivity shock introduced
in (3).

The quadratic cost of adjusting its nominal price between periods is
given by:
$$\\frac{\\phi\_p}{2}\[\\frac{P\_t(i)}{{\\pi\_{t-1}^a \\pi^{1-a}P\_{t-1}(i)}}-1\]^2Y\_t$$

The firm chooses *P*<sub>*t*</sub>(*i*) for all *t* = 0, 1, 2, ... to
maximise its total real market value proportional to:
$$E\_0\\sum\_{t=0}^\\infty \\beta^t\\Lambda\_t\[\\frac{D\_t(i)}{P\_t}\]$$
where the firm’s real profits are measured by:

$$\\frac{D\_t(i)}{P\_t}=\[\\frac{P\_t(i)}{P\_t}\]^{1-\\theta\_t}Y\_t-\[\\frac{P\_t(i)}{P\_t}\]^{-\\theta\_t}(\\frac{W\_t}{P\_t})(\\frac{Y\_t}{Z\_t})-\\frac{\\phi}{2}\[\\frac{P\_t(i)}{\\pi\_{t-1}^a \\pi^{1-a}P\_{t-1}(i)}\]^2Y\_t\\tag{12}$$

The Value function of this optimisation problem is:
$$v=maxE\_t\\sum\_{t=0}^\\infty\\beta^t\\Lambda\_t{\\frac{D\_t(i)}{P\_t}}$$

As such, the Bellman Equation can be constructed as:

$$v=\\beta^t\\Lambda\_t{\\frac{D\_t(i)}{P\_t}} + \\beta^{t+1}E\_t\\Lambda\_{t+1}{\\frac{D\_{t+1}(i)}{P\_{t+1}}}$$
$$v=\\beta^t\\Lambda\_t\[(\\frac{P\_t(i)}{P\_t})^{1-\\theta\_t}Y\_t-(\\frac{P\_t(i)}{P\_t})^{-\\theta\_t}(\\frac{W\_t}{P\_t})(\\frac{Y\_t}{Z\_t})-\\frac{\\phi}{2}(\\frac{P\_t(i)}{\\pi\_{t-1}^a \\pi^{1-a}P\_{t-1}(i)})^2Y\_t\] + \\beta^{t+1}E\_t\\Lambda\_{t+1}\[(\\frac{P\_{t+1}(i)}{P\_{t+1}})^{1-\\theta\_{t+1}}Y\_{t+1}-$$
$$(\\frac{P\_{t+1}(i)}{P\_{t+1}}\]^{-\\theta\_{t+1}}(\\frac{W\_{t+1}}{P\_{t+1}})(\\frac{Y\_{t+1}}{Z\_{t+1}})-\\frac{\\phi\_p}{2}\[\\frac{P\_{t+1}(i)}{\\pi\_{t}^a \\pi^{1-a}P\_{t}(i)}\]^2Y\_{t+1}\]$$

#### The FOC with respect to *P*<sub>*t*</sub>(*i*)

$$ \\frac{\\partial v}{\\partial P\_t(i)} = \\beta^t\\Lambda\_t(1-\\theta\_t)(\\frac{P\_t(i)}{P\_t})^{-\\theta\_t}(\\frac{1}{P\_t})Y\_t-\\beta^t\\Lambda\_t\[(-\\theta\_t\\frac{P\_t(i)}{P\_t})^{-\\theta\_t-1}(\\frac{1}{P\_t})(\\frac{W\_t}{P\_t})(\\frac{Y\_t}{Z\_t})\]-$$
$$\\beta^t\\Lambda\_t\[\\phi\_p(\\frac{P\_t(i)}{\\pi\_{t-1}^a \\pi^{1-a}P\_{t-1}(i)}-1)(\\frac{1}{\\pi\_{t-1}^a \\pi^{1-a}P\_{t-1}(i)})Y\_t\] -\\beta^{t+1}E\_t\\Lambda\_{t+1}\\phi\_p\[(\\frac{P\_{t+1}(i)}{\\pi\_t^a\\pi^{1-a}P\_{t}(i)}-1)(\\frac{-P\_{t+1}(i)Y\_{t+1}}{\\pi\_t^a\\pi^{1-a}P\_{t}(i)^2})\] =0$$

Next, in order to cancel out most *λ*<sub>*t*</sub>, *Y*<sub>*t*</sub>
and *P*<sub>*t*</sub>’s, multiply through by
$\\frac{P\_t}{\\lambda\_t Y\_t}$:

$$\\beta^t(1-\\theta\_t)(\\frac{P\_t(i)}{P\_t})^{-\\theta\_t} + \\beta^t\[\\theta\_t(\\frac{P\_t(i)}{P\_t})^{-\\theta\_t-1}(\\frac{W\_t}{P\_t})(\\frac{1}{Z\_t})\] - \\beta^t\\phi\_p\[(\\frac{P\_t(i)}{\\pi\_{t-1}^a \\pi^{1-a}P\_{t-1}(i)}-1)(\\frac{P\_t}{\\pi\_{t-1}^a \\pi^{1-a}P\_{t-1}(i)})\] +$$
$$\\beta^{t+1}\\phi\_pE\_t(\\frac{\\Lambda\_{t+1}}{\\Lambda\_{t}})(\\frac{P\_{t+1}(i)}{\\pi\_t^a\\pi^{1-a}P\_{t}(i)}-1)(\\frac{P\_{t+1}(i)}{\\pi\_t^a\\pi^{1-a}P\_{t}(i)})(\\frac{Y\_{t+1}}{Y\_t})(\\frac{P\_t}{P\_t(i)})=0$$
$$(1-\\theta\_t)(\\frac{P\_t(i)}{P\_t})^{-\\theta\_t} + \\theta\_t(\\frac{P\_t(i)}{P\_t})^{-\\theta\_t-1}(\\frac{W\_t}{P\_t})(\\frac{1}{Z\_t}) - \\phi\_p\[(\\frac{P\_t(i)}{\\pi\_{t-1}^a \\pi^{1-a}P\_{t-1}(i)}-1)(\\frac{P\_t}{\\pi\_{t-1}^a \\pi^{1-a}P\_{t-1}(i)})\] +$$
$$\\beta\\phi\_pE\_t(\\frac{\\Lambda\_{t+1}}{\\Lambda\_{t}})(\\frac{P\_{t+1}(i)}{\\pi\_t^a\\pi^{1-a}P\_{t}(i)}-1)(\\frac{P\_{t+1}(i)}{\\pi\_t^a\\pi^{1-a}P\_{t}(i)})(\\frac{Y\_{t+1}}{Y\_t})(\\frac{P\_t}{P\_t(i)})=0$$

and (11) with equality for all *t* = 0, 1, 2, ...,

## The Efficient Level of Output and Output Gap

A social planner for this economy who can overcome the frictions
associated with monetary trade, sluggish price adjustment, and the
monopolistically competitive structure of the intermediate
goods-producing sector chooses *Q*<sub>*t*</sub> and
*n*<sub>*t*</sub>(*i*) for all *i* ∈ \[0,1\] to maximize the social
welfare function

$$E\_0\\sum\_{t=0}^{\\infty}\\beta^ta\_t\[\\ln(Q\_t-\\gamma Q\_{t-1})-\\int\_0^1n\_t(i) di\]$$
subject to

$$Z\_t\[\\int\_0^1n\_t(i) di\]^{\\frac{\\theta\_t}{\\theta\_t-1}} \\ge Q\_t$$
As such, the Bellman Equation of this model is:

$$v(Q\_{t-1}) = a\_t\[\\ln(Q\_t-\\gamma Q\_{t-1})-\\int\_0^1n\_t(i) di\] + \\beta E\_tv(Q\_t,Q\_{t+1}) + \\Xi \[Z\_t(\\int\_0^1n\_t(i) di)^{\\frac{\\theta\_t}{\\theta\_t-1}} - Q\_t\]$$

#### The FOC with respect to *Q*<sub>*t*</sub>:

$$\\frac{\\partial v(Q\_{t-1})}{\\partial Q\_t} = \\frac{a\_t}{Q\_t-\\gamma Q\_{t-1}} + \\beta E\_t\\frac{\\partial v(Q\_t, Q\_{t+1})}{\\partial Q\_t} - \\Xi =0$$
We know that

$$\\frac{\\partial v(Q\_{t-1})}{\\partial Q\_{t-1}} = \\frac{a\_t}{Q\_t-\\gamma Q\_{t-1}} (-\\gamma)$$

Therefore, when iterating forward, we find that:
$$\\frac{\\partial v(Q\_{t})}{\\partial Q\_{t}} = \\frac{a\_{t+1}}{Q\_{t+1}-\\gamma Q\_{t}} (-\\gamma)$$

Subbing $\\frac{\\partial v(Q\_{t})}{\\partial Q\_{t}}$ back in gives:

$$\\frac{\\partial v(Q\_{t-1})}{\\partial Q\_t} = \\frac{a\_t}{Q\_t-\\gamma Q\_{t-1}} + \\beta E\_t\\frac{a\_{t+1}}{Q\_{t+1}-\\gamma Q\_{t}} (-\\gamma) - \\Xi =0$$
Multiply through by (−1):

$$ \\frac{a\_t}{Q\_t-\\gamma Q\_{t-1}} - \\beta E\_t\\frac{a\_{t+1}}{Q\_{t+1}-\\gamma Q\_{t}} (\\gamma)  = \\Xi$$

#### The FOC with respect to *n*<sub>*t*</sub>:

$$\\frac{\\partial v(Q\_{t-1})}{\\partial n\_t} = a\_t (-1) + \\Xi Z\_t \\frac{\\theta\_t}{\\theta\_t -1} (\\int\_0^1n\_t(i)^\\frac{\\theta\_t -1}{\\theta\_t} di)^\\frac{\\theta\_t}{\\theta\_t - 1} (\\frac{\\theta\_t -1}{\\theta\_t}) n\_t(i)^{\\frac{\\theta\_t -1}{\\theta\_t}-1}=0$$
$$ a\_t + \\Xi Z\_t  (\\int\_0^1n\_t(i)^\\frac{\\theta\_t -1}{\\theta\_t} di)^\\frac{1}{\\theta\_t - 1} n\_t(i)^{\\frac{-1}{\\theta\_t}}=0$$
$$  \\Xi Z\_t  (\\int\_0^1n\_t(i)^\\frac{\\theta\_t -1}{\\theta\_t} di)^\\frac{1}{\\theta\_t - 1} n\_t(i)^{\\frac{-1}{\\theta\_t}}=a\_t$$

The Feasibility Constraint of this problem is:
$$(\\int\_0^1n\_t(i)^\\frac{\\theta\_t -1}{\\theta\_t} di)^\\frac{\\theta\_t}{\\theta\_t - 1} \\ge \\frac{Q\_t}{Z\_t}$$
Rearranging the Feasibility Constraint gives:

$$(\\int\_0^1n\_t(i)^\\frac{\\theta\_t -1}{\\theta\_t} di)^\\frac{1}{\\theta\_t - 1} \\ge (\\frac{Q\_t}{Z\_t})^\\frac{1}{\\theta\_t}$$
Therefore

$$\\Xi Z\_t (\\frac{Q\_t}{Z\_t})^\\frac{1}{\\theta\_t}n\_t(i)^{\\frac{-1}{\\theta\_t}}=a\_t$$

## Log-Linearisation:

# 2.2 The Representative Household

The household’s preferences are described by the expected utility
function :

The household then carries Mt units of money into period t + 1, chosen
subject to the budget constraint (1):

# Stationarity Variables:

Given the following stationary variables

*y*<sub>*t*</sub> = *Y*<sub>*t*</sub>/*Z*<sub>*t*</sub>, *c*<sub>*t*</sub> = *C*<sub>*t*</sub>/*Z*<sub>*t*</sub>, *π*<sub>*t*</sub>, *r*<sub>*t*</sub>, *m*<sub>*t*</sub> = (*M*<sub>*t*</sub>/*P*<sub>*t*</sub>)/*Z*<sub>*t*</sub>, *q*<sub>*t*</sub> = *Q*<sub>*t*</sub>/*Z*<sub>*t*</sub>, *x*<sub>*t*</sub>, *μ*<sub>*t*</sub>, *g*<sub>*t*</sub>, *λ*<sub>*t*</sub> = *Z*<sub>*t*</sub>*Λ*<sub>*t*</sub>, *a*<sub>*t*</sub>, *z*<sub>*t*</sub> = *Z*<sub>*t*</sub>/*Z*<sub>*t* − 1</sub>, *u*<sub>*t*</sub>,  and *θ*<sub>*t*</sub>

We can rewrite the system of equations as

$$\\begin{array}{l}
{c}y\_{t}=c\_{t}+\\frac{\\phi\_{p}}{2}\\left(\\frac{\\pi\_{t}}{\\pi\_{t-1}^{\\alpha} \\pi^{1-\\alpha}}-1\\right)^{2} y\_{t}, \\\\
\\\\
\\ln \\left(a\_{t}\\right)=\\rho\_{a} \\ln \\left(a\_{t-1}\\right)+\\varepsilon\_{a t}, \\\\
\\\\
\\ln \\left(z\_{t}\\right)=\\ln (z)+\\varepsilon\_{z t}, \\\\
\\\\
\\ln \\left(u\_{t}\\right)=\\rho\_{u} \\ln \\left(u\_{t-1}\\right)+\\varepsilon\_{u t}, \\\\
\\\\
\\lambda\_{t}=\\frac{a\_{t}z\_{t}}{z\_{t} c\_{t}-\\gamma c\_{t-1}}-\\beta \\gamma E\_{t}\\left(\\frac{a\_{t+1}}{z\_{t+1} c\_{t+1}-\\gamma c\_{t}}\\right), \\\\
\\\\
\\lambda\_{t}=\\beta r\_{t} E\_{t}\\left(\\frac{\\lambda\_{t+1}}{z\_{t+1} \\pi\_{t+1}}\\right), \\\\
\\\\
\\frac{a\_{t}}{\\delta}\\left\[\\ln \\left(m^{\*}\\right)-\\ln \\left(m\_{t}\\right)+\\ln \\left(u\_{t}\\right)\\right\]-a\_{t}\\left(\\frac{\\phi\_{m}}{2}\\right)\\left(\\frac{z\_{t} m\_{t}}{z m\_{t-1}}-1\\right)^{2} \\\\
-a\_{t} \\phi\_{m}\\left(\\frac{z\_{t} m\_{t}}{z m\_{t-1}}-1\\right)\\left(\\frac{z\_{t} m\_{t}}{z m\_{t-1}}\\right) \\\\
+\\beta \\phi\_{m} E\_{t}\\left\[a\_{t+1}\\left(\\frac{z\_{t+1} m\_{t+1}}{z m\_{t}}-1\\right)\\left(\\frac{z\_{t+1} m\_{t+1}}{z m\_{t}}\\right)^{2}\\left(\\frac{z}{z\_{t+1}}\\right)\\right\] \\\\
=\\lambda\_{t}\\left(1-\\frac{1}{r\_{t}}\\right), \\\\
\\frac{a\_{t}}{\\delta}\\left\[\\ln \\left(m^{\*}\\right)-\\ln \\left(m\_{t}\\right)+\\ln \\left(u\_{t}\\right)\\right\]-a\\\_{t}\\left(\\frac{\\phi\_{m}}{2}\\right)\\left(\\frac{z\_{t} m\_{t}}{z m\_{t-1}}-1\\right)^{2} \\\\ -a\_{t} \\phi\*{m}\*\\left(\\frac{z\_{t} m\_{t}}{z m\_{t-1}}-1\\right)\\left(\\frac{z\_{t} m\_{t}}{z m\_{t-1}}\\right) \\\\ +\\beta \\phi\_{m} E\_{t}\\left\[a\_{t+1}\\left(\\frac{z\_{t+1} m\_{t+1}}{z m\_{t}}-1\\right)\\left(\\frac{z\_{t+1} m\_{t+1}}{z m\_{t}}\\right)^{2}\\left(\\frac{z}{z\_{t+1}}\\right)\\right\] \\\\ =\\lambda\_{t}\\left(1-\\frac{1}{r\_{t}}\\right), 
\\end{array}$$

and,

In steady state we can write the following per definitions:

$$y\_{t}=y,\\ c\_{t}=c,\\ \\pi\_{t}=\\pi,\\ r\_{t}=r m\_{t}=m,\\ q\_{t}=q,\\ x\_{t}=x,\\ \\\\ 
\\mu\_{t}=\\mu,\\ g\_{t}=g,\\ \\lambda\_{t}=\\lambda,\\ a\_{t}=a=1,\\ z\_{t}=z,\\ u\_{t}=u=1, \\\\ 
\\text {and } \\theta\_{t}=\\theta$$

# Log-linearisation:

## Applying The Taylor Method of Linear Approximation

We apply the Taylor throughout the following section as follows:

For a function *f*(*x*<sub>*t*</sub>) input *x*<sub>*t*</sub> , we apply
the Taylor method such that:
$$f(x\_t) = f(X^{SS}) + \\frac{df(x)}{x\_t} (x\_t(i) - x^{SS})$$

Using the approximation:
$$\\begin{aligned}
&x\_t - x^{SS} \\approx x^{SS} \\hat{x}\_{t}
\\\\
&\\text{where } \\hat{x}\_{t} = \\ln(x\_t)-\\ln(x^{SS})
\\\\
&\\text{For short, we write: } x^{SS} \\equiv x
\\\\
&\\text{(i.e. no time subscript)}
\\end{aligned}$$

## Equation (1) in Paper

From equation (1) in the appendix, we obtain the following:

$$\\begin{array}{l}
y\_{t} &= c\_t + \\frac{\\phi\_{p}}{2} \\cdot \\left\[ \\frac{\\pi\_{t}}{{\\pi\_{t-1}}^{\\alpha} \\pi^{1-\\alpha}} -1 \\right\]^{2} \\cdot y\\\\
&=c\_{t} + \\frac{\\phi\_{p}}{2} \\cdot \\left(\\frac{\\pi\_{t}}{{\\pi\_{t-1}}^{\\alpha} \\pi^{1-\\alpha}} \\right)^2 \\cdot y\_{t} - \\phi\_{p} \\cdot 
\\frac{\\pi\_{t}}{{\\pi\_{t-1}}^{\\alpha} \\pi^{1-\\alpha}} \\cdot y\_{t} + \\frac{\\phi\_{p}}{2} \\cdot y\_{t}\\\\
&= c\_t + p\_{1} - p\_{2} + p\_{3}
\\end{array}$$

Now, we can apply the Taylor method to each *p*<sub>*i*</sub>, such that
we get:

$$\\begin{array}{l}
\\
p\_{1}^{SS}&=\\frac{\\phi\_{p} \\cdot y}{2}\\\\\\left\[\\frac{dp\_{1}}{dy\_{t}} \\right\]^{SS} &= \\frac{\\phi\_{p}}{2}\\\\\\left\[\\frac{dp\_{1}}{d\\pi\_{t}} \\right\]^{SS} &= \\frac{\\phi\_{p} \\cdot y}{\\pi}\\\\\\left\[\\frac{dp\_{1}}{d\\pi\_{t-1}} \\right\]^{SS} &= - \\frac{\\phi\_{p} \\cdot y}{\\pi}
\\end{array}$$

### p1

Therefore, we can rewrite *p*<sub>1</sub> using the Taylor method, as:

$$\\begin{aligned}
p\_{1} = \\frac{\\phi\_{p} \\cdot y}{2} + \\frac{\\phi\_{p}}{2} y \\cdot \\hat{y\_{t}} + \\frac{\\phi\_{p} \\cdot y}{\\pi} \\pi \\cdot \\hat{\\pi\_{t}} - \\frac{\\phi\_{p} \\cdot y}{\\pi}\\pi \\cdot \\hat{\\pi\_{t-1}}\\\\
= \\frac{\\phi\_{p} \\cdot y}{2} + \\frac{\\phi\_{p} \\cdot y \\cdot \\hat{y\_{t}} }{2} + \\phi\_{p} \\cdot y \\cdot \\hat{\\pi}\_{t} - \\alpha \\cdot \\phi\_{p} \\cdot y \\cdot \\hat{\\pi}\_{t-1} \\\\
\\end{aligned}$$

### p2

and for *p*<sub>2</sub>

$$\\begin{aligned}
\\left\[ p\_{2} \\right\]^{SS} &= \\phi\_{p} y
\\\\
\\left\[ \\frac{dp\_{2}}{dy\_{t}} \\right\]^{SS} &= \\phi\_{p}
\\\\
\\left\[ \\frac{dp\_{2}}{d\\pi\_{t}} \\right\]^{SS} &= \\frac{\\phi\_{p} y}{\\pi}
\\\\
\\left\[ \\frac{dp\_{2}}{d\\pi\_{t-1}} \\right\]^{SS} &= - \\alpha \\frac{\\phi\_{p} y}{\\pi}
\\end{aligned}$$

Then, writing the Taylor approximation for *p*<sub>2</sub>

$$\\begin{aligned}
p\_{2} &= \\phi\_{p} y + \\phi\_{p} y \\hat{y}\_{t} + \\frac{\\phi\_{p} y}{\\pi} \\pi \\hat{\\pi}\_{t} - \\alpha \\frac{\\phi\_{p} y}{\\pi} \\pi \\hat{\\pi}\_{t-1}\\\\
&= \\phi\_{p} y + \\phi\_{p} y \\hat{y}\_{t} + \\phi\_{p} y \\hat{\\pi}\_{t} - \\alpha \\phi\_{p} y \\hat{\\pi}\_{t-1}
\\end{aligned}$$

### p3

Lastly, repeating the same process for the last term *p*<sub>3</sub>

$$\\begin{aligned}
\\left\[ p\_{3} \\right\]^{SS} &= \\frac{\\phi\_{p} y} {2}\\\\\\left\[ \\frac{dp\_{3}}{dy\_{t}} \\right\]^{SS} &= \\frac{\\phi\_{p}}{2}
\\end{aligned}$$

Then, writing the Taylor approximation for *p*<sub>3</sub>

$$p\_{3} = \\frac{\\phi\_{p} y} {2} + \\frac{\\phi\_{p}}{2}y \\hat{y}\_{t}$$

Putting it all together with
*y*<sub>*t*</sub> = *c* + *p*<sub>1</sub> − *p*<sub>2</sub> + *p*<sub>3</sub>
we get:

$$\\begin{aligned}
y\_{t} = & \\ c\_t  +\\left\[ \\overbrace{\\frac{\\phi\_{p} \\cdot y}{2}}^{A} + \\overbrace{\\frac{\\phi\_{p} \\cdot y \\cdot \\hat{y\_{t}} }{2}}^{B} + \\overbrace{\\phi\_{p} \\cdot y \\cdot \\hat{\\pi}\_{t}}^{C} - \\overbrace{\\alpha \\cdot \\phi\_{p} \\cdot y \\cdot \\hat{\\pi}\_{t-1}}^{D} \\right\] \\\\ & \\ - \\left\[ \\overbrace{\\phi\_{p} y}^{2A} + \\overbrace{\\phi\_{p} y \\hat{y}\_{t}}^{2B} + \\overbrace{ \\phi\_{p} y \\hat{\\pi}\_{t}}^{C} - \\overbrace{\\alpha \\phi\_{p} y \\hat{\\pi}\_{t-1}}^{D} \\right\] + \\left\[ \\overbrace{\\frac{\\phi\_{p} y} {2}}^{A} + \\overbrace{\\frac{\\phi\_{p}}{2}y \\hat{y}\_{t}}^{B} \\right\] \\\\= &\\  c\_{t} + A + B + C -D - 2A - 2B - C + D + A + B\\\\
\\end{aligned}$$

Now, using
$y = c + \\frac{\\phi\_{p} \\cdot y}{2} - \\phi\_{p} y + \\frac{\\phi\_{p} y} {2} = c$,
we subtract y on both sides, such that

$$\\begin{aligned}
A + B + C &- D - 2A - 2B - C + D + A + B = 0
\\text{ and thus, }
\\\\
y\_{t} - y &= c\_t - c
\\\\
\\Rightarrow y \\cdot \\hat{y}\_t &= c \\cdot \\hat{c}\_t
\\\\
\\Rightarrow \\hat{y}\_t &= \\hat{c}\_t
\\end{aligned}$$

## Equation (5) in paper:

$$\\Lambda\_t = \\frac{a\_t}{C\_t-\\gamma C\_{t-1}} - \\beta \\gamma E\_t \\left\[ \\frac{a\_{t+1}}{C\_{t+1} - \\gamma C\_t} \\right\]$$

Using
*c*<sub>*t*</sub> = *C*<sub>*t*</sub>/*Z*<sub>*t*</sub> *λ*<sub>*t*</sub> = *Z*<sub>*t*</sub> ⋅ *Λ*<sub>*t*</sub>,  and *z*<sub>*t*</sub> = *Z*<sub>*t*</sub>/*Z*<sub>*t* − 1</sub>
we can rewrite the above equation using its stationary variables:

$$\\begin{array}{l}
\\lambda\_{t} / Z\_t =\\frac{a\_{t}}{Z\_{t} c\_{t}-\\gamma Z\_{t-1} c\_{t-1}}-\\beta \\gamma E\_{t} \\left(\\frac{a\_{t+1}}{Z\_{t+1} c\_{t+1}-\\gamma Z\_{t-1} c\_{t}} \\right)\\\\
\\text{ times each term with: } \\left(Z\_{t-1} / Z\_{t-1}\\right) \\text{ and } (Z\_{t} / Z\_{t}) \\text{ respectively} \\\\
\\lambda\_{t} =\\frac{a\_{t} z\_{t}}{z\_{t} c\_{t}-\\gamma c\_{t-1}}-\\beta \\gamma E\_{t}\\left(\\frac{a\_{t+1}}{z\_{t+1} c\_{t+1}-\\gamma c\_{t}}\\right)
\\end{array}$$

Once again, for simplicity, we separate the equation into two parts:

$$\\lambda\_{t}=\\frac{a\_{t} z\_{t}}{z\_{t} c\_{t}-\\gamma c\_{t-1}}-\\beta \\gamma E{t}\\left(\\frac{a\_{t+1}}{z\_{t+1} c\_{t+1}-\\gamma c\_{t}}\\right)\\
= a\_1 + \\beta \\gamma E\_t (a\_2)$$

Now we can determine the taylor approximations individually

### a1

$$
$$

The similarity between *a*<sub>1</sub> and *a*<sub>2</sub> means that
some of the steps will yield very similar results:

### a2

$$
$$

Thus, we have
$$\\lambda\_t = a\_1 - \\beta \\gamma E\_t (a\_2) \\text{ which we can expand, and } 
\\\\
\\lambda = \\frac{a z}{(z  -\\gamma)c } - \\beta \\gamma \\frac{a}{(z-\\gamma) c}$$

### Lambda

$$
$$

subtracting *λ* from both sides of the equations to get
*λ*<sub>*t*</sub> − *λ* on the left side, we get:

$$
$$ From the paper we know that *a* = 1,
*E*<sub>*t*</sub>*â*<sub>*t* + 1</sub> = (*ρ*<sub>*a*</sub>*â*<sub>*t*</sub>),
and *E*<sub>*t*</sub>*ẑ*<sub>*t* + 1</sub> = 0, and thus:

$$
$$ The common denominator can be removed by multiplying both sides by
(*z**c*−*γ**c*)<sup>2</sup> and then we divide by c

$$
$$ We know *ĉ*<sub>*t*</sub> = *ŷ*<sub>*t*</sub> and *c* = *y*

$$
$$

From the Appendix, we can use the fact that
$y \\lambda=\\frac{(z-\\beta \\gamma)}{(z-\\gamma)}$

$$(z-)(z-) =

(z-)(z-*{a}) *{t}-z *{t}-(z<sup>{2}+</sup>{2}) *{t}+z *{t-1} + z E*{t}
\_{t+1}$$

yielding the final result:
(*z*−*γ*)(*z*−*β**γ*)*λ̂*<sub>*t*</sub> = (*z*−*γ*)(*z*−*β**γ**p*<sub>*a*</sub>)*â*<sub>*t*</sub> − *γ**z**ẑ*<sub>*t*</sub> + *z**γ**ŷ*<sub>*t* − 1</sub> + *β**γ**z**E*<sub>*t*</sub>*ŷ*<sub>*t* + 1</sub> − (*z*<sup>2</sup>+*β**γ*<sup>2</sup>)*ŷ*<sub>*t*</sub>

## Uhlig’s Method of Linearisation

For the following equation we will apply Uhlig’s method. First, we
provide a small illustration of how the method is applied

For the equation *f*(*x*<sub>*t*</sub>), we use the fact that:
$$\\hat{x}\_t = \\ln(x\_t) - \\ln(x) \\\\
\\text{ where x } \\equiv x^{SS}$$
Then, *f*(<sup>*S**S*</sup>) is used to simplify *f*(*x*<sub>*t*</sub>)
where *x*<sub>*t*</sub> is replaced accodring to
*x*<sub>*t*</sub> = *x* ⋅ *e*<sup>*x̂*<sub>*t*</sub></sup> Additionally,
the result
*e*<sup>*x*<sub>*t*</sub> + *y*<sub>*t*</sub></sup> ≈ 1 + *x*<sub>*t*</sub> + *y*<sub>*t*</sub>
is also used

## Equation (7)

$$\\lambda\_{t}=\\beta r\_{t} E\_{t}\\left(\\frac{\\lambda\_{t+1}}{z\_{t+1} \\pi\_{t+1}}\\right)$$

The steady state equation follows as

$$\\lambda = \\beta r \\frac{\\lambda} {z \\pi} \\\\
\\Rightarrow 1=\\frac{\\beta r} {z \\pi}$$

Now, substituting each variable in the fashion similar to
*λ*<sub>*t*</sub> = *λ**e*<sup>*λ̂*<sub>*t*</sub></sup>

$$\\begin{array}{l}
\\lambda\_{t}=\\beta r\_{t} E\_{t}\\left\[\\frac{\\lambda\_{t+1}}{z\_{t+1} \\pi\_{t+1}}\\right\]\\\\
\\Rightarrow \\lambda e^{\\hat{\\lambda}\_t}=\\beta r e^{\\hat{r}\_{t}} E\_{t}\\left\[\\frac{\\lambda e^{\\hat{\\lambda}\_{t+1}}}{z e^{\\hat{z}\_{t+1}} \\pi e^{\\hat{\\pi}\_{t+1}}} \\right\]\\\\
\\Rightarrow \\lambda\\left(1+\\hat{\\lambda}{t}\\right)=\\frac{\\beta r \\lambda}{z \\pi} \\quad E\_{t}\\left\[\\frac{\\left(1+\\hat{\\lambda}\_{t+1}-\\hat{z}\_{t+}-\\hat{\\pi}\_{t+1}+\\hat{r}\_{t}\\right)}{1}\\right\]\\\\
\\Rightarrow \\left(1+\\hat{\\lambda}\_{t}\\right)= E\_{t}\\left\[1+\\hat{\\lambda}\_{t+1}-\\hat{z}\_{t+}-\\hat{\\pi}\_{t+1}+\\hat{r}\_{t}\\right\]\\\\
\\text{using }{ E\_t }\[\\hat{z}\_{t+1}\]=0\\\\
\\Rightarrow 1+\\hat{\\lambda}\_{t} = 1+E\_{t}\\left\[\\hat{\\lambda}\_{t+1}-\\hat{\\pi}\_{t+1}+\\hat{r}\_{t}\\right\]\\\\
\\therefore \\hat{\\lambda}\_{t}=\\hat{r}\_{t}+E\_{t}\\left\[\\hat{\\lambda}\_{t+1} - \\hat{\\pi}\_{t+1}\\right\]\\\\
\\end{array}$$

## Equation (9)

As indicated in the Appendix of the paper, substituting for the steady
state conditions in equation (9) yields $$
$$

## Equation (13)

$$\\begin{array}{l}
\\theta\_{t}-1=& \\theta\_{t}\\left(\\frac{a\_{t}}{\\lambda\_{t}}\\right)-\\phi\_{p}\\left(\\frac{\\pi\_{t}}{\\pi\_{t-1}^{\\alpha} \\pi^{1-\\alpha}}-1\\right)\\left(\\frac{\\pi\_{t}}{\\pi\_{t-1}^{\\alpha} \\pi^{1-\\alpha}}\\right) \\\\
&+\\beta \\phi\_{p} E\_{t}\\left\[\\left(\\frac{\\lambda\_{t+1} y\_{t+1}}{\\lambda\_{t} y\_{t}}\\right)\\left(\\frac{\\pi\_{t+1}}{\\pi\_{t}^{\\alpha} \\pi^{1-\\alpha}}-1\\right)\\left(\\frac{\\pi\_{t+1}}{\\pi\_{t}^{\\alpha} \\pi^{1-\\alpha}}\\right)\\right\]
\\end{array}$$
In Steady State this becomes

$$
$$

## Equation (14)

$$1=\\frac{z\_{t}}{z\_{t} q\_{t}-\\gamma q\_{t-1}}-\\beta \\gamma E\_{t}\\left\[\\left(\\frac{a\_{t+1}}{a\_{t}}\\right)\\left(\\frac{1}{z\_{t+1} q\_{t+1}-\\gamma q\_{t}}\\right)\\right\]$$

The LHS of the equation, instead of approximating, the log of 1 is zero,
so that is used instead For the RHS, we continue as before, by
separating the function into simpler terms

$$\\begin{array}{l}
z\_1 = \\frac{z\_{t}}{z\_{t} q\_{t}-\\gamma q\_{t-1}} \\\\
z\_2 = \\left(\\frac{a\_{t+1}}{a\_{t}}\\right)\\left(\\frac{1}{z\_{t+1} q\_{t+1}-\\gamma q\_{t}}\\right)
\\end{array}$$
\### Z1

$$
\\end{array}$$

Now we can expand the linearisation equation for *z*<sub>1</sub>

$$z\_1 = \\frac{z}{z q-\\gamma q} 
- \\frac{\\gamma q}{(z q-\\gamma q)^2} z \\cdot \\hat{z}\_t
- \\frac{z^{2}}{(z q-\\gamma q)^2} q \\cdot \\hat{q}\_t
+ \\frac{z \\gamma}{(z q-\\gamma q)^2} q \\cdot \\hat{q}\_{t-1}$$

### Z2

$$
$$

Therefore, we have *z*<sub>2</sub> Recall a=1 $$
$$
Now for $\\beta \\gamma E\_t z\_2$, using $E\_t \\hat{a}\_{t+1}=\\rho\_a\\hat{a}\_t$
$$
$$

### Together

Now, we can write out
0 = *z*<sub>1</sub> − *β**γ**E*<sub>*t*</sub>*z*<sub>2</sub> Using
$$z\_1-z\_1^{SS} - \\beta \\gamma (z\_2 - z\_2^{SS}) \\approx z\_1 \\hat{z\_1} - z\_2 \\hat{z\_2}\\\\
\\Rightarrow \\text{subtract from the RHS: } \\frac{z}{z q-\\gamma q}-\\beta \\gamma \\frac{a}{a z q-\\gamma a q}$$

$$
$$

Multiply both sides by $(z q-\\gamma q)^{2} \\frac{1}{q}$

$$
$$

Finally, we subtract
$$\\left\[\\frac{z}{z q-\\gamma q}-\\beta \\gamma \\frac{a}{a z q-\\gamma a q} \\right\] \\cdot (z q-\\gamma q)^{2} \\frac{1}{q}\\\\
= z(z -\\gamma) -\\beta \\gamma (z- \\gamma)\\\\
=z^2 -\\gamma z-\\beta \\gamma z + \\beta \\gamma^2$$
to yield the final solution:

$$
$$

## Equation (15)

$$x\_{t}=y\_{t} / q\_{t}\\\\
\\text{Steady State: }\\\\
x = y/p$$

Now,
$$x\_{t}=y\_{t} / q\_t\\\\
\\Rightarrow x e^{\\hat{x} t}=\\frac{y e^{\\hat{y} t}}{q e^{\\hat{q} t}}\\\\
\\Rightarrow\\left(1+\\hat{x}\_{t}\\right)=\\left(1+\\hat{y}\_{t}-\\hat{q}\_{t}\\right)\\\\
\\therefore \\quad \\hat{x}\_{t}=\\hat{y}\_{t}-\\hat{q}\_{t}$$

## Equation (16)

ln (*r*<sub>*t*</sub>/*r*) = *ρ*<sub>*r*</sub>ln (*r*<sub>*t* − 1</sub>/*r*) + *ρ*<sub>*π*</sub>ln (*π*<sub>*t* − 1</sub>/*π*) + *ρ*<sub>*x*</sub>ln (*x*<sub>*t* − 1</sub>/*x*) + *ε*<sub>*r**t*</sub>

Directly applying Uhlig’s method using
*r*<sub>*t*</sub> = *r* ⋅ *e*<sup>*r̂*<sub>*t*</sub></sup> for each
variable of the equation yields the required result:

$$\\ln \\left\[\\frac{r e^{\\hat{r} t}}{r}\\right\]=\\operatorname{\\rho\_r} \\ln \\left\[\\frac{r e^{\\hat{r}\_{t-1}}}{r}\\right\]+\\rho{\\pi} \\ln \\left\[\\frac{\\pi e^{\\hat{\\pi}\_{t-1}}}{n}\\right)+\\rho\_x \\ln \\left(\\frac{x e^{\\hat{x}\_{t+1}}}{x}\\right)+\\varepsilon\_{rt} \\\\
\\therefore \\quad \\hat{r}\_{t}=\\rho\_{r} \\hat{r}\_{t-1}+\\rho\_{\\pi} \\hat{\\pi}\_{t-1}+\\rho x \\hat{x}\_{t-1}+\\varepsilon\_{r t}$$

## Equation (17)

*μ*<sub>*t*</sub> = *z*<sub>*t*</sub>(*m*<sub>*t*</sub>/*m*<sub>*t* − 1</sub>)*π*<sub>*t*</sub>

Applying uhlig’s Method:

$$
$$

## Equation (18)

This equation

*g*<sub>*t*</sub> = (*y*<sub>*t*</sub>/*y*<sub>*t* − 1</sub>)*z*<sub>*t*</sub>

Using the Steady State solution

*g* = *z*

Yields the following solution, using Uhlig’s method:

$$\\begin{array}{l}
g\_{t}=\\left(\\frac{y\_{t}}{y\_{t-1}}\\right) z\_{t}\\\\
\\Rightarrow ge^{g\_{t}}=\\left\[\\frac{y e^{\\hat{y}\_{t}}}{y e^{\\hat{y}\_{t-1}}}\\right\] z e^{\\hat{z}\_{t}}\\\\
\\Rightarrow \\quad\\left(1+\\hat{g}\_{t}\\right)=\\left(1+\\hat{y}\_{t}-\\hat{y}\_{t-1}+\\hat{z}\_{t}\\right)\\\\
\\therefore \\quad \\hat{g}\_{t}=\\hat{y}\_{t}-\\hat{y}\_{t-1}+\\hat{z}\_{t}
\\end{array}$$

## Equation (2)

$$\\begin{array}{l}
& \\ln \\left(a\_{t}\\right)=p\_{a} \\ln \\left(a\_{t-1}\\right)+\\varepsilon\_{a t} \\\\
& \\ln \\left(a e^{\\hat{a}\_{t}}\\right)=p\_{a} \\ln \\left(a e^{\\hat{a}\_{t-1}}\\right)+\\varepsilon\_{a t} \\\\
\\Rightarrow & \\ln (a)+\\hat{a}\_{t}=\\rho\_{a} \\ln (a)+p\_{a} \\hat{a}\_{t-1}+\\varepsilon\_{a t} \\\\
&\[a =1\] \\\\
\\therefore \\quad \\hat{a}\_{t} &=\\rho\_{a} \\hat{a}\_{t-1}+\\varepsilon\_{a t}
\\end{array}$$

## Equation (3)

$$\\begin{array}{l}
\\ln(z\_t)=\\ln(z) + \\varepsilon\_{z t}\\\\
\\Rightarrow \\ln\\left(z e^{\\hat{z}\_t}\\right) =\\ln (z)+\\varepsilon\_{z t}\\\\
\\Rightarrow  \\ln (z)+\\hat{z}\_{t}=\\ln (z)+\\varepsilon\_{z t}\\\\
\\therefore \\hat{z}\_t = \\varepsilon\_{z t}
\\end{array}$$

## Equation (4)

$$\\begin{array}{l}
& \\ln \\left(u\_{t}\\right)=p\_{u} \\ln \\left(u\_{t-1}\\right)+\\varepsilon\_{u t} \\\\
& \\ln \\left(u e^{\\hat{u}\_{t}}\\right)=p\_{u} \\ln \\left(u e^{\\hat{u}\_{t-1}}\\right)+\\varepsilon\_{u t} \\\\
\\Rightarrow & \\ln (u)+\\hat{u}\_{t}=\\rho\_{u} \\ln (u)+p\_{u} \\hat{u}\_{t-1}+\\varepsilon\_{u t} \\\\
&\[u =1\] \\\\
\\therefore \\quad \\hat{u}\_{t} &=\\rho\_{u} \\hat{u}\_{t-1}+\\varepsilon\_{u t}
\\end{array}$$

## Equation (10)

$$\\begin{array}{l}
& \\ln \\left(\\theta\_{t}\\right)=\\left(1-\\rho\_{\\theta}\\right) \\ln (\\theta)+\\rho\_{\\theta} \\ln \\left(\\theta\_{t-1}\\right)+\\varepsilon\_{\\theta t} \\\\
\\Rightarrow & \\ln \\left(\\theta e^{\\hat{\\theta}\_{t}}\\right)=\\left(1-\\rho\_{\\theta}\\right) \\ln (\\theta)+\\rho\_{\\theta} \\ln \\left(\\theta e^{\\hat{\\theta}{t-1}}\\right)+\\varepsilon\_{\\theta t} \\\\
\\Rightarrow & \\ln (\\theta)+\\hat{\\theta}\_{t}=\\ln (\\theta)-\\rho\_{\\theta} \\ln (\\theta)+\\rho\_{\\theta} \\ln (\\theta)+\\rho\_{\\theta} \\hat{\\theta}\_{t-1}+\\varepsilon\_{\\theta t} \\\\
\\therefore & \\quad \\hat{\\theta}\_{t}=\\rho\_{\\theta} \\hat{\\theta}\_{t-1}+\\varepsilon\_{\\theta t}
\\end{array}$$

using the normalisation
*ê*<sub>*t*</sub> =  − (1/*ϕ*<sub>*p*</sub>)*θ̂*<sub>*t*</sub>

and

*ρ*<sub>*e*</sub> = *ρ*<sub>*θ*</sub>
We can rewrite:
$$\\begin{array}{l}
\\hat{\\theta}\_{t}=\\rho\_{\\theta} \\hat{\\theta}\_{t-1}+\\varepsilon\_{\\theta t}\\\\
\\Rightarrow -\\left(1 / \\phi\_{p}\\right) \\cdot \\hat{\\theta}\_{t} =  \\hat{e}\_t = -\\left(1 / \\phi\_{p}\\right) \\left\[ \\rho\_{\\theta} \\hat{\\theta}\_{t-1}+\\varepsilon\_{\\theta t} \\right\]\\\\
\\Rightarrow \\hat{e}\_t =  \\rho\_{e} \\hat{e}\_{t-1}+\\varepsilon\_{e t}
\\end{array}$$
