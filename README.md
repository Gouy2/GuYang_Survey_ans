# GuYang_Survey_ans
Survey for MSc (ai4s) —— answer

**Detailed code is in ans.ipynb**

#### 5th.Solution ideas：

Dice Roll Probability Problem → Calculate minimum rolls needed for 68% confidence of mean within ±1% of true average (3.5)

Solution Path:
Expected Value (3.5) → Target Range [3.465, 3.535] → Monte Carlo Simulation → Binary Search/Linear Search → N ≈ 2381 rolls

Key Points:
• Fair die (1-6) → μ = 3.5
• Required accuracy: ±1% = ±0.035
• Confidence level: >68%
• Uses Central Limit Theorem


#### 6th.Solution ideas：

Unique Letter Permutations Problem → Calculate total unique arrangements of letters in a sentence, handling repeating letters

Solution Path:
Input String → Clean Text (remove spaces & non-alpha) → Letter Frequency Count → Apply Permutation Formula

Key Points:
• Formula: n! / (n₁!×n₂!×...×nₖ!)
• n = total letters
• nᵢ = frequency of each letter
• Case-insensitive
• Excludes spaces & punctuation


#### 8th.Solution ideas：

Planetary Alignment Problem → Find next alignment of Mercury, Venus, and Earth after initial alignment

Solution Path:
Planet Periods [88, 225, 365.25 days] → Daily Angular Positions → Check Alignment (within 1°) → Search First Match

Key Results:
• Same Side: 21,679 days
• Any Side: 5,275 days
• Method: Angular Difference Check
• Tolerance: ±1°

Key Points:
• Uses modulo for orbital position
• Handles 360° wraparound
• Daily check assumption
• Two possible scenarios (same/any side)
