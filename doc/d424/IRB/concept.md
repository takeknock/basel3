# RWA for corporate and bank exposure
$Correlation(R)= 0.12 \cdot \frac{1-e^{-50\cdot PD}}{1-e^{-50}} + 0.24 \cdot (1-\frac{1-e^{-50\cdot PD}}{1-e^{-50}})$ 
Marcro factor と個別企業の間の相関。

$\mathrm{Maturity Adjustment(b)}=[0.11852-0.05478\cdot ln(PD)]^2$

$\mathrm{Capital Requirement(K)}=[LGD\cdot N(\frac{G(PD)}{\sqrt{(1-R)}}+\sqrt{\frac{R}{1-R}}\cdot G(0.999))-PD\cdot LGD]\cdot \frac{(1+(M-2.5)\cdot b)}{1-1.5\cdot b}$
$K = UL - EL$
$= LGD \times \bar{PD} \times EAD - LGD \times PD \times EAD$
Gは正規分布の累積分布関数の逆関数。G(0.999)は99.9%タイル点(端に0.1%しか分布の面積が残らない点)の値
$\mathrm{Risk Weighted Asset(RWA)} = K \cdot 12.5 \cdot EAD$


# A-IRB

LGDは与信枠ごとにLGDを推定する必要がある。

# F-IRB

# The standards