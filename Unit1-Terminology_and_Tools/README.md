# Unit 1: Terminology and Basics
## Assignment, for Sept. 3, 2019:
#### Math review problems in [HW0 document](https://github.com/ATMOcanes/ATM651_IntroAtmDynamics/blob/master/Unit1-Terminology_and_Tools/HW/Homework0.pdf) 
#### Read, and write answers to all problems in, [Mapes Ch. 1](https://github.com/brianmapes/ConvectionShortCourse/blob/master/BookDraft_PDFs_2019_July/Chapter1_StuffInSpace.pdf) 
#### Read, and know all problems in, Wallace & Hobbs Ch. 1 (oral in class)

### Classes of mathematical objects we will use 
------------------------
|  | 0D domain | 1D | 2D | 3D | 4D |
|---|---|---|---|---|---|
|0D range |a number|const line|const map|const(3D)|time independent const(3D)|
|1D  |a random variable (PDF)| y=f(x) curve | 2D scalar map| 3D scalar field | evolving 3D field|
|2D  |a 2D vector|2D vectors along a line|2D flow: **kinematics**|hor. vectors in 3D or evolving 2D flow|evolving hor. vectors in 3D|
|3D  |a 3D vector|3D vectors along a line|a plane of 3D vectors| **3D flow at an instant** | **evolving 3D flow**|
|ND  |a ND vector|matrix algebra|arrays|arrays|abstract phase spaces|


### Pure math concepts 
------------------------
| Word | Meaning | Math notation(s) | Conceptual Sketch |
|---|---|---|---|
|Function, argument, value, domain, range ||||
|First derivative|slope, gradient, tendency, velocity for pos(t)|study [notation](https://en.wikipedia.org/wiki/Notation_for_differentiation) |rate of change wrt. domain variable|
|Integral|[anti-derivative](https://en.wikipedia.org/wiki/Fundamental_theorem_of_calculus) (cumulative sum)|(plus arbitrary constant of integration)|CDF from PDF|
|Second derivative |curvature, Laplacian, acceleration for pos(t)|*-Σ k<sub>i</sub><sup>2</sup> sin(k<sub>i</sub> x)* when applied to *Σ sin(k<sub>i</sub>x)*|emphasizes small scales; edge finder in imagery|
|Inverse Laplacian, informally ∇<sup>-2</sup>|double integral|*-Σ k<sub>i</sub><sup>-2</sup> sin(k<sub>i</sub>x)* when applied to *Σ sin(k<sub>i</sub> x)*|smoothed, emphasizes largest scales. Two constants of integration|
|Mixed second derivative |saddle shape measure, ...|||

### Physical measures and SI units (Mapes book Ch. 1) 
------------------------
| Word | Meaning | Math | Concept Sketch |
|---|---|---|---|
|meter|human-sized unit of measure of space|1e-7 **Earth**'s equator-pole distance||
|kilogram|human-sized unit of measure of mass|1e-3 mass of 1 m^3 of **water**||
|Kelvin or *centigrade* degree|convenient-resolution T scale|1e-2 ...**water**...||
|second|human-sized time scale|...**Earth**...||
|liter|||
|Bar, atmosphere|mean weight of **Earth**'s air at sea level| coincidence! |What is a Pascal?|
|flux|amount of xxx passing through a square meter per second| units tell the story| UNITS! |
|flow (of a river)|amount of water passing per second| how related to flux?| UNITS! |
|Vertically integrated flux|like an *atmospheric river* | units tell the story | UNITS! |
|force || " | Newtons |
|pressure |as a flux| " | Pascals |
|pressure |related to force| " | Pascals |

### Physical processes and relations
------------------------
| Word | Meaning | Math | Concept Sketch |
|---|---|---|---|
|Flux|x|x|x|
|Net flux into a region (flux *convergence*) ||||
|Time rate of change ||||
|Sources and sinks ||||
|Conservation ||||
|Advection ||||
|Diffusion ||||
|Balance ||||

