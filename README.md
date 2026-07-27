# A-B-Testing

**A/B/C/D Test: Homepage CTA Button**
**Background**
**Eniac tested four variations of their homepage call-to-action button:**

**Version	Color	Copy**
A	White	"SHOP NOW"
B	Red	"SHOP NOW"
C	White	"SEE DEALS"
D	Red	"SEE DEALS"

**Metric Tracked**
**Click-through rate (CTR)** — clicks ÷ total visits to the homepage. This was the sole metric used to determine a winning version; a version is only declared superior if its CTR difference is statistically significant.

**Hypotheses**
**H₀ (null)**: All four versions have the same CTR.
**H₁ (alternative)**: At least one version's CTR differs from the others.

**Test Design**
Significance level: 95% (5% false-positive tolerance)
Statistical power: 80%
Minimum detectable effect (MDE): 20% — a deliberately large threshold, trading sensitivity to small differences for a shorter required runtime given Eniac's traffic volume.
Baseline CTR: ~2% (existing "SHOP NOW" button)
Daily traffic: ~7,142 visits/day
Sample size / duration: Calculated via an online power calculator, extended to 14 days to span two full business cycles.
Test window: November 2 – November 16, 2021

**Next Steps**
Load the experiment data.
Compute CTR for each of the four versions.
Identify the version with the highest CTR.
Assess (informally) whether the results look conclusive.
(Next lesson) Run a formal chi-square significance test on the CTR differences to confirm whether the observed winner is statistically real or could be due to chance.
