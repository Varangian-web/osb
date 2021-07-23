### Dilution Ventilation

**Dilution ventilation i**s general ventilation used to bring down the concentration of the hazardous contaminants in the air. It is generally not as effect as LEV systems


**Heat Control Ventilation** is the control of the atmospheric conditoin indoors for the purpos of preventing discomfort or injury


### Dilution Ventilation Guidance #airflow  #ventilation #dilution

[[Industrial Ventilation Manual.pdf#page=30]]

1. Select  from available data the amount of air required for satisfactory dilution of contaminant. 
2.  Locate the exhaust opening nera the sources of contamination.
3.  Locate the air supply and exhaust outlets such that the air passes through the zone of contamination. The operator should remain between the air supply and the source of the contaminant.
4.  Replace exhausted air by use of a replacement air system. This replacement air should be heated during cold weather. Dilution ventilation systems usually handle large quantities of air by means of low pressure fans. 
5. Avoid re-entry of the exhausted air by discahrging the exhaust high above the roof line or by assuring that no widow, outdoor air intakes, or other such opening are located near the exhaust discharge.


### Dilution Ventilation for Health #airflow  #health #ventilation 

Dilution ventilation is used most often to cntrol the vapors from organic liquids with the TLV of 100 ppm or higher.


$RateOfAccumulation = RateOfGeneration - RateOfRemoval$

or 

$VdC = Gdt - Q'Cdt$

where:

V - volume of room
G - rate of generation
Q' - effective volumetric flow rate
C - concentration of gas or vapor
t - time
As steady state,

$dC = 0$
$Gdt = Q'Cdt$

$\int_{t1}^{t2}Gdt = \int_{t1}{t2}Q'Cdt$

at constant concentration, C and uniform generatoin rate, G,

$G(t_2-t_1) = Q' C (t_2 - t_1)$

Due to incomplete mixing, a K value is introduced:
[[Industrial Ventilation Manual.pdf#page=32]]
$Q' = \dfrac{Q}{K}$

where:

Q - actual ventilation rate, cfm
Q' - effective ventilation rate, cfm
K - a factor to allow for incomplete mixing

$Q = (\dfrac{G}{C})K$

Where K is based on several considerations: #design #duct #consideration #parameters 

- The efficiency of mixing and distribution of replacement air introduced into the room or space being ventilated
- The toxicity of the solvent. Although TLV and toxicity are not the same.
	-- Slightly toxic material : TLV > 500 ppm
	-- Moderately toxic material: TLV $\leq$ 100 - 500ppm
	-- Highly toxic material: TLV < 100 ppm
-  A judgement of any other circumstances which the industrial hygienist determiend to be of importanve based on experience and the individual problem. Included in these criteria are:

1. Duration of the process, operational cycle, and normal locations of workers relative to source of contamination.
2. Location and number of point of generation of the contaminant in the workroom or area.
3. Seasonal changes in the amount of natural ventilation
4. Reduction in operational effectiveness of mechanical air moving devices
5. Other circumstances which may affect teh concentraiotn of hazardous material in the breathing working zone.


K value ranges from 1  -> 10


### Calculation Dilution for Steady-State Concentrations

$Q' = \dfrac{G}{C}$

stdin : Generation rate
stdout: Flow of Uncontaminated Air


Rate of Generation for liquid solvent is:

$$ G = \dfrac{Constant \times SG \times ER}{MW}$$

where :

G = generation rate, cfm
constact = the volume in $ft^3$ that 1 pt of liquid when vaporised will occupy at STP
SG = Specific gravity of volatile liquid
ER = evaporation rate of liquid, pts/min
MW = molecular weight of liquid

Thus, $Q' = \dfrac {G}{C}$ ->

$Q' = \dfrac {403 \times 10^6 \times SG \times ER}{MW \times C}$

Example :[[Industrial Ventilation Manual.pdf#page=33]]



Contaminant Concentration Buildup #contaminant #airflow 

$$\dfrac{dC}{G-Q'C} = \dfrac{dt}{V}$$

which can be integrated to yield
$$ln(\dfrac{G - Q'C_2}{G-Q'C_1})= - \dfrac{Q'(t_2-t_1)}{V}$$

$$\Delta t = - \dfrac{V}{Q'}[ln(\dfrac{G-Q'C_2}{G-Q'C_1})]$$

_1 -  initial condition
_2  -final condition

$$\Delta t = - \dfrac {V}{Q'}[ln(\dfrac{G-Q'C_2}{G-Q'C_1})]$$

$C_1=0$  ->
$\Delta t = - \dfrac{V}{Q'}[ln(\dfrac{G-Q'C_2}{G})]$


If $C_2$ needs to be determiend at $\Delta t$ and $C_1 = 0$ then
#concentration #formula
$C_2 = \dfrac{G[1-e(-\dfrac{Q' \Delta t}{V})]}{Q'}$
#ppm
convert to ppm $C_2 \cdot 10^6$
	
$VdC = -Q'Cdt$

$ln(\dfrac{C_2}{C_1})= \dfrac{Q'}{V}(t_2 - t_1)$

or, 

$C_2 = C-1 e^{-\dfrac{Q'(t_2 - t_1)}{V}}$

Example [[Industrial Ventilation Manual.pdf#page=34]]

for multiple substances the effects of hazardous substances are additive, unless known others

$\sum_i^n\dfrac{C_i}{TLV_i}$


Example calcing for LEL dilution [[Industrial Ventilation Manual.pdf#page=35]]

Notes:
1. Since LEL is expressed in %(parts per 100) rathern than ppm (parts per millio as for the TLV) the coefficient of 1,000,000 becomes 100.

2. $S_f$ is a safety coefficient which depends on the percent of the LEL necessary safe conditons. In most ovens and drying enclosures it has nee found desirable to maintain vapor concentratoin at not more than 25% of the LEL at all times in all parts of the oven. In proplerly ventilatied continue. In batch ovens, with good  air distrubutions, the existence of peak drying rates required an $S_f$

3. B is a constant which takes into account the fact that the lower explosiv]e limit of a solvent vapor or air mixture decreases at elevated temperatures. 

$$
B=
\begin{cases}
1  & T \leq 250F \\
0.7 & T \gt 250F
\end{cases}
$$


### Heat Balance 

#formula #heat_balance #heat_loading

$$\Delta S = (M-W) \pm C \pm R - E$$

where:

$\Delta S$ - change in body heat content
$(M - W)$ - total metabolism - external work performed
C - convecting heat exchange
E - evaporative heat loss

May modes of heat exhast include:

- convection
- radiation
- evaporation

standard worker of weight 70 kg(154 lbs) and has a body surface area of 1.7 $m^2$ or 19.4 $ft^2$


#### Convection #convection

$C = 0.65 V_a^{0.6}(t_a - t_sk)$

where:

C - convective heat excahnge, Btu/h
$V_a$ - air veloctity, fpm
$t_a$ - air templerature, F
$t_sk$ - mean weighted skin temperature, @ 95 F

#### Radiation #radiation

$R = 1.5(tw-t_sk)$

where:
R - radiant heat exchange, Btu/h
t_w - mean radiant temperature, F
t_sk - mean weighted skin temperature

#### Evaporation #evaporation_skin

$E = 2.4 V_a^0.6 (\rho_sk - \rho_a)$

where:

E - evaporative heat loss, Btu/h
V_a - air velocity, fpm
$\rho_a$ - water vapor pressure of ambient air, mmHg
$\rho_sk$ - water vapor pressure on the skin assume to 42 mmH at 95 F skin


#### Metabolic response to heat 
[[Industrial Ventilation Manual.pdf#page38]]o


#### Aclimatization

Generally, people in good health



#### Acute Heat Disorder 
placeholder for heat loss prevention program
[[Heat Loss Prevention Program notes]]

** Heat stroke**
Heat stroke is a life-threatening conditon which withou exception demands immediate conditon. Characteristically htis condition is caused when - sweating has ceased, the skin is hot and dry, and keep body temperature is above 104 F. The person be either diaphoretic, semiconcious, unconscious or agitated.o


**Heat Exhaustion**


Work cost by used of the energy6

[[Industrial Ventilation Manual.pdf#page=39]]o


Assessment of Heat Stress and Heat Strain

Heat Stress is defined by enviromnetal measurements of air temperature, humidity, air flow rate, the leve of radiant heat excahge and evaluation of a person's metalbolic heat production rate from execise and/or work. 

Heat strain is defined as the cost to each person facing heat stress. Although all people work,ing at the smae intensity in the same environemnt face the asme level of heat stress, each is under a unique level of heat strain.

Dry-bulb method to evaluate heat stress 
[[Industrial Ventilation Manual.pdf#page=40]]

Wet-bulb, globe temperature (WBGT) $\in$ index of heat stress

$WBGT = 0.7 t_nwb + 0.2 t_g  + 0.1 t_a$

where 

$t_nwb$ - natural web-bulb tempearature
$t_g$ - globe temperature


$WBGT = 0.7 t_nwb + 0.3 t_g$

WBGT does not account for skin convection, and metabolic heat production.


**Decreased Systemic Arterial Blood Pressure**
A fall in blood pressure of more than about 40 Torr in about 3.5 minutes fro someone working in a heat stress idnicate a heat-induced disability. Reduced consciouscness, feeling of weakness, vision disturbances, and other signs and symptoms are lilkely to follow.


