$base = 40$
$subRank = 1 \to 5$
$rankIndex = 0_{Bronze} \to 7_{Legendary}$

$linearGrowth = 21 \times (subRank - 1 )$
$crossRankMultiplier = 6^{rankIndex}$

$subRankModifier = subRank^{1.15}$
$withinRankMultiplier = 1.25^{subRankModifier}$

$Fortitude(rankIndex, subRank) = Round(base \times  crossRankMultiplier \times withinRankMutliplier + linearGrowth)$
$FortitudeDrain = (2 + 0.25\alpha_{isAlpha} + 0.1_{\sum(extraAbilities)})^{BST/100}$
