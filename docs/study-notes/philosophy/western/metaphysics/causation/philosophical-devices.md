# Philosophical Devices

From: [Philosophical Devices Proofs, Probabilities, Possibilities, and Sets David Papineau](https://global.oup.com/academic/product/philosophical-devices-9780199651733)

**Correlation and Causation**

&#x20;Popular meme: "Correlation is not causation"

True, but they are deeply connected; a correlation between A and B is always (if not merely coincidental) due to some form of causal connection between A and B.

Generally, the correlation between A and B implies either A is causing B, B is causing A, or some confounder C ("common cause") is causing both A and B.&#x20;

* We can screen off the confounder effect by randomized selection and then a control group-based trial (Randomized Controlled Trials).
* Need to take care of selection bias and p-hacking

Spurious correlation implies P(H| A and F) = P(H|F) (F being a confounder, H, A being apparently correlated)

#### Simpson's Paradox

Correlations can be reversed after removing any confounder effect. This can happen when the correlating variables and the confounder have causal effects in reverse directions.&#x20;

Say A decreases the probability of H, all else being the same. And M increases the probability of H and all else being the same.&#x20;

P(H|A) can be > P(H|\~A) because of marginalizing over M and \~M because M correlates more with A and P(H|M) is high. But when accounting for M it can be that: P(H|A and M) < P(H|\~A and M)

For more, see:

{% embed url="https://plato.stanford.edu/entries/paradox-simpson/" %}

{% embed url="https://en.wikipedia.org/wiki/Simpson's_paradox" %}
