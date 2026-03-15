# Theorem Of Wisdom: Bayes’ Theorem As The Most Possible Rational Way Of Making Decisions

[Sandra(Yijia)](https://www.linkedin.com/in/yijia-sandra-cai/) Cai


July 2, 2025


**Abstract**


Often time, people are struggling with making decisions. According to Harvard [Business](https://hbr.org/2023/12/a-simple-way-to-make-better-decisions#:~:text=Various%20sources%20suggest%20that%20the,how%20we'll%20say%20it.) Re[view,](https://hbr.org/2023/12/a-simple-way-to-make-better-decisions#:~:text=Various%20sources%20suggest%20that%20the,how%20we'll%20say%20it.) average adults make 33,000 to 35,000 decisions each day, including easy and hard ones.
However, how many of them are actually close to the best absolute rationality for the best possible outcome is yet a myth. Let alone the decision making process should be driven by good
reasoning and rationale, which normally consume a certain amount of brain power to do so.
Bayes’ Theorem, a theorem in probability theory that describes the probability of an event occurring under certain known conditions, created by Mathematician Thomas Bayes in 1763, can be a
useful tool for making it happen given its comprehension, causality, and factorization of objective
facts. Coming from a scientific approach of observing and evaluating things we are experiencing,
it provides a quantitative method of weighing out different options choices to believe. In other
words, the leanest way of touching absolute rationality.

## **1 Introduction**


Bayes’ Theorem, categorized under Conditional Probability, which is a way of predicting the probability
of an event when there was another event already occurred. Considering the first event as event A and
the second corresponding event as event B, this probability follows the format of being written as


_P_ ( _B|A_ )


, notation for the probability of B given A. If event A has 0 influence over the probability of event B,
then the conditional probability of event B is simply


_P_ ( _B_ )


. In this case, event A and event B are also viewed as independent events. If the events are not
independent, the probability of both events A and B occurring simultaneously, which is also known as
the intersection of A and B, is defined by


_P_ ( _AandB_ ) = _P_ ( _A_ ) _∗_ _P_ ( _B|A_ )


Figure 1: Mathematician Thomas Bayes (1702            - 1761)


1


, considering the influence on event B from event A. In this case, the conditional probability


_P_ ( _B|A_ )


can be calculated by

_P_ ( _B|A_ ) = _[P]_ [(] _[AandB]_ [)]

_P_ ( _A_ )


, which is considered valid only when
_P_ ( _A_ ) _>_ 0


.
As an useful means to reason information, for example, when FBI is backtracking what has happened at the crime scene to identify the criminal; considering there will be a massive pouring rain
given the density of drips dropping from the sky in the next minutes; knowing other people are going
to cry when they frown their forehead and curve their mouth corners. Information reasoning exists in
everywhere of our daily lives. However, the reality has complex variables and grey zones, for example, a homeless person suddenly wins the lottery ticket, people may think this person cheated, which
presents an only-right-or-only-wrong mindset without factorizing other possible reasons contributing
to the event altogether, which includes


_No.1_ _This_ _person_ _cheated_


and
_No.2_ _This_ _person_ _has_ _been_ _observing_ _which_ _number_ _wins_ _lottery_ _the_ _most_


and


_No.3_ _This_ _person_ _used_ _Bayes’_ _Theorem_ _to_ _calculate_ _the_ _chance_ _of_ _winning_ _at_ _that_ _time_


. Therefore, it is important to maintain a mindset of probability, displaying all of the possible reasons
of the event and then choose the one that has the biggest probability. Intuition is the most used tool
for reasoning in people’s lives, which is to make decisions based on the most intuitively possible reason
relevant to the event but not Bayes’ Theorem. Sometimes, it can be dangerously misleading.

## **2 Practicality**


**2.1** **Scenario** **1:** **Who** **is** **going** **to** **be** **more** **drunk**


Ben and Jerry are drinking together. Based on their alcohol tolerance, Ben will get drunk when
drinking 9 shots out of 10 total shots whereas Jerry will get drunk when drinking only 1 shot out of
total 10 shots. This means Ben has higher alcohol tolerance than Jerry.
Now, suppose we observe that someone is drunk, and we want to determine whether it’s more likely
to be Ben or Jerry. To apply Bayes’ Theorem properly, we need to consider both the likelihood and
prior probabilities.
The likelihood represents how probable it is to observe someone being drunk given that it’s a
specific person:

_P_ ( _drunk|Ben_ ) = [9]

10 [= 90%]

_P_ ( _drunk|Jerry_ ) = [1]

10 [= 10%]

However, to determine who is more likely to be the drunk person (i.e., _P_ ( _Ben|drunk_ ) vs. _P_ ( _Jerry|drunk_ )),
we also need to consider the prior probabilities. If we assume both Ben and Jerry are equally likely to
be the person we’re observing initially:


_P_ ( _Ben_ ) = _P_ ( _Jerry_ ) = 50%


Using Bayes’ Theorem:


_P_ ( _Ben|drunk_ ) = _[P]_ [(] _[drunk][|][Ben]_ [)] _[ ×][ P]_ [(] _[Ben]_ [)]

_P_ ( _drunk_ )


2


_P_ ( _Jerry|drunk_ ) = _[P]_ [(] _[drunk][|][Jerry]_ [)] _[ ×][ P]_ [(] _[Jerry]_ [)]

_P_ ( _drunk_ )


Where _P_ ( _drunk_ ) = _P_ ( _drunk|Ben_ ) _×P_ ( _Ben_ )+ _P_ ( _drunk|Jerry_ ) _×P_ ( _Jerry_ ) = 0 _._ 9 _×_ 0 _._ 5+0 _._ 1 _×_ 0 _._ 5 = 0 _._ 5
Therefore:
_P_ ( _Ben|drunk_ ) = [0] _[.]_ [9] _[ ×]_ [ 0] _[.]_ [5] = 90%

0 _._ 5

_P_ ( _Jerry|drunk_ ) = [0] _[.]_ [1] _[ ×]_ [ 0] _[.]_ [5] = 10%

0 _._ 5

This shows that if we observe someone drunk, it’s more likely to be Ben (90%) than Jerry (10%),
because Ben gets drunk more frequently despite having higher tolerance. This demonstrates how
Bayes’ Theorem properly combines likelihood with prior probability to make rational inferences.


**2.2** **Scenario** **2:** **Is** **the** **elevator** **going** **to** **crash**


Some people are afraid of taking elevators. When the elevator suddenly slows down from one floor to
another, people start to think about it is going to crash down, and here is what people are reasoning:


_Severe_ _turbulence_ _in_ _the_ _speed_ _of_ _the_ _elevator_ _were_ _observed_


and then there are following possible reasons:


_a._ _elevator_ _crashes_ _down_


and
_b._ _elevator_ _is_ _normal_ _but_ _it_ _is_ _overused_ _and_ _a_ _little_ _bit_ _clunky_


However, if an elevator crashes down, the likelihood of the people in this elevator feeling obvious
differences in the speed of the elevator is


_P_ ( _severe_ _turbulence|elevator_ _crashes_ _down_ ) = 100%


. When the elevator is overused but is functioning normally, assuming it is 1 time out of 10 times of
the total usage, then the likelihood of crashing down is


_P_ ( _severe_ _turbulence|elevator_ _is_ _overused_ ) = 10%


. In this case, elevator crashing down has stronger ability of explaining people feeling severe turbulence
than elevator being overused, which means the likelihood is higher. Hence people will reason the
phenomenon with elevator is crashing down and they will feel great panicked.
However, elevators being overused is way more common to happen in reality, not crashing down.
So we notice there is the problem of utilizing the maximum likelihood estimation - when we infer
the cause from the phenomenon, we have to not only consider the ability of explaining but also the
the basic probability of this cause itself occurring, which is prior probability, which is independent
to the phenomenon itself. According to Elevator [Injury](https://www.elevatorinjurylawyer.com/common-accidents-and-injuries/how-safe-are-elevators/) Lawyer, the chance of dying in one elevator
crash-down is about 1 in 10.5 million, which means if a person takes an elevator once per day, it
takes 28767 years for this person to experience this event. Therefore, the prior probability of elevator
crashing down is

1
_P_ ( _elevator_ _crashing_ _down)_ =
28767 _∗_ 365 [= 9] _[.]_ [52] _[ ∗]_ [10] _[−]_ [8]

. However, it is common to experience elevator being overused and it does not have an averaged speed
while going up or down per floor consistently, which means we can estimate the prior probability


_P_ ( _elevator_ _overused)_ _=_ _0.9_


. Then we multiply two reasons’ prior probability and likelihood to make a comparison, we have


_elevator_ _crashing_ _down_ : 100% _∗_ 9 _._ 52 _∗_ 10 _[−]_ [8] = 9 _._ 52 _∗_ 10 _[−]_ [8]


, and
_elevator_ _overused_ : 10% _∗_ 0 _._ 9 = 0 _._ 09


. It is noticed that when elevator has severe turbulence, elevator being overused is 94537.8 times
elevator getting crashed down, which means there is almost no need to worry about the crash down.


3


**2.3** **Interpretation**


Now that we can come to an interpretation of Bayes’ Theorem. We have


_P_ ( _reason|phenomenon_ ) = _[P]_ _[(reason)][ ∗]_ _[P]_ [(] _[phenomenon][|][reason]_ [)]

_P_ ( _phenomenon_ )


, which means the left side of the equation is information reasoning calculates the probability of
inferring the cause after observing the phenomenon, which is also called the posterior probability; the
first numerator from left to right is prior probability, the second numerator is the likelihood which is
the probability of observing a phenomenon given the cause, also known as the ability of the cause to
explain phenomenon; the denominator is the basic probability of the phenomenon itself given the listed
various reasons. However, regardless of reasons, the denominator remains the same. Therefore, we can
compare numerators, which is, the result of prior probability multiplying likelihood, to calculate the
best possible reason. It is also noticed that the denominator is to scale the likelihood of the cause by
a fixed ratio, which provides a role of standardization. Hence we have


_posterior_ _probability_ = _prior_ _probability ∗_ _standardized_ _likelihood_

## **3 Summary**


We can now draw a conclusion that the process of Bayes’ Theorem is . . .


1. Observe the phenomenon


2. List all of the possible causes


3. Calculate different prior probabilities of different causes


4. Calculate different likelihood of different causes


5. Compare the multiplication of prior probability and likelihood


6. Choose the highest multiplication to be the most possible cause to the phenomenon


It also allows us to observe new phenomena, and to continuously update and iterate the posterior
probabilities of causes, which is also considered The Generalization of Bayesian Theory. The the
process from the Bayes’ Theorem to The Generalization of Bayesian Theory is a good interpretation
for science reasoning too. In science reasoning, we have . . .


  - Propose theoretical hypotheses based on observations


  - Continuously update confidence in the hypothetical theory based on new observations


Bayes’ Theorem is currently considered to be the most powerful scientific view on earth in science and
philosophy. According to Cornell [University,](https://blogs.cornell.edu/info2040/2018/11/28/bayes-theorem-and-the-existence-of-god/) it can be discussed with the existence of God. This is
not only useful to scientific world, but also our daily lives, with the examples provided above, because
there are many causes to a certain phenomenon and people are limited to their own experiences coming
up with different causes, hence endowing different prior probability to different causes. Different prior
probability combined with different existing experience will lead to different basic confidence on a
certain phenomenon, let alone the causes that lack of data as the backup to be a valid proof. Hence,
calculate the likelihood of the cause for new evidence based on reliable data, thus updating the posterior
probability of each cause. When there is more and more evidence, people turn to have similar or same
basic confidence on a certain phenomenon.
Discussing this further, Bayes’ Theorem is a good evidence against conspiracy theory because the
likelihood is either 0 or almost 100%, so we have


_P_ ( _observed_ _phenomenon|conspiracy_ ) _≈_ 100%


. However, the prior probability is extremely low,


_P_ ( _conspiracy_ ) _≈_ _extremely_ _low_


4


, and
_P_ ( _observed_ _phenomenon|conspiracy_ ) _≈_ _extremely_ _low_


. Therefore, in the current environment of political history in the making and media [infodemic](https://www.who.int/health-topics/infodemic#tab=tab_1) out
bursting, people who place trust on conspiracy is using maximum likelihood estimation to think about
problems, not Bayes’ mindset, and given the ability of conspiracy to explain certain phenomena, it
is highly difficult for people to change their mind on this because the posterior probability keeps
increasing when iterating with new data. Therefore, if people are not willing to change their belief on
prior probability, there is almost no way to reach a common ground, which is not within the scope of
rational thinking and discussion.
Bayes’ Theorem is worthy to be learned by everyone given the interpretation and embodiment of
scientific view and validation. It is probably the most possible rational way for human beings to reach
an iteration-friendly best-optimal decision making process while doing the calculations.


5


