# Basic of flow(유) cytometry(세포측정), Part I: Gating and data analysis

- 측정하고자 하는 세포집단의 세포들을 각각 하나씩 측정하여 분석하는 특징을 가짐 

- 유액 상태의 입자나 세포를 감지하기 위해 일정 파장을 띄는 형광이 표지된 항체 같은 형광염색소의 표지가 필수적, 형광을 감지 하기 위해 광원인 레이저 광원을 통한 형광의 발광 작용 이용


#### Fluorescence(형광)

*Result of process in certain molecules which are called fluorophores, or fluorescent dyes.*

-> fluorophores또는 형광 염료라고하는 특정분자의 process의 결과를 형광이라고합니다.

*A fluorescent compound absorbs light, which causes an electron in the compound to be raised to a higher energy level.*

-> 형광 화합물은 화합물 내의 전자를 높은 에너지 레벨로 상승 시키는 빛을 흡수합니다.

*The  excited electron quickly decays, emitting excess energy as a photon of light.*

-> excited된 전자는 빠르게 붕괴되고, 과도한 에너지를 빛의 광자로 방출합니다.

*The emitted light is called fluorescence.* 

-> 방출된 빛을 형광이라고 합니다. 

<br>

- Absorption(흡수, 통합) spectrum : The wave length range over which a flouorescent compound can be excited.

- Emission(빛,열, 가스등의 배출) spectrum : The range or emitted wavelengths of a flouorescent compound, it is a longer wavelenth than the absorption wavelengths.

- Stokes Shift : difference between the excitation and emission wavelengths

  ​			excitation과 emission wavelength 사이의 차이

A fluorescent probe is a fluorophore designed to localize within a specific region of a cell or respond to a specific stimulus.

-> 형광 probe는 세포의 특정 영역 내에 위치하거나 특정 자극에 반응하도록 디자인된 형광물질 입니다.

<br>

**Fluorescence**(형광, 발광) - 파장의 빛을 흡수하는 물질의 성질 

**Fluorophore is a molecule that is capable of fluorescing(fluoresce, 형광을 내다).**

-> 형광물질(fluorophore)은 형광을 낼 수 있는 분자



1. Fluorophore in Ground State

   Ground state에서 molecule은 상대적으로 저-에너지, 안정적인 configuration,그리고 형광을 내지 않음. 


2. Absorption of Light Energy

   외부에서 빛이 들어와  형광 분자를 hit 할 경우 분자는 빛에너지를 흡수할 수 있음

3. Fluorophore in Excited state

   Excitation : 흡수된 에너지가 충분할 경우 molecule은 excited sate라 불리는 고 에너지 state에까지 도달하는 프로세스

4. Energy Loss

   Fluorophore가 high-energy configuration 일때는 unstable하기때문에 결국 semi-stable이라고 부르는lowest-energy excited state를 취합니다.

   fluorophore가 excited states에 있는 시간을 excited lifetime이라고함, 굉장히 짧게 지속됨

5. Fluorescence Emission

   fluorophore가 semi-stable excites state에서 rearrange하여 ground state로 돌아감 그리고 과잉된 에너지가 빛으로 방출됨

   방출 된 광은 흡수 된 광보다 에너지가 낮고 따라서 장 파장이다. 이는 방출되는 빛의 색이 흡수된 빛의 색과 다르다는 것을 의미함

<br>

Absorbed light(Absorption) -> Excitation -> Loss of Energy -> Emission(Emitted light)

<br>

Excitation Range(Spectrum) - 특정 파장 범위의 에너지의 흡수

Emission Range(Spectrum) - 다른 특정 파장 범위의 에너지로 재방출 

<br>

**요약**

- Fluorophore는 빛 에너지를 흡수할때 excited state에 도달할 수 있는 분자로 빛 에너지를 방출 함
- Excitation, Excited lifetime, Emission라 불리는 세가지 Process를 Fluorescence(형광)이라고 합니다.
- Excitation과 Emission 파장이 다르기 때문에, 흡수되거나 방출된 빛은 가시 스펙트럼 상의 다른색 또는 영역으로써 검출 가능함

<br>

Fluorescence Excitation

- Excitation maximum : fluorophore는 특정 wavelength에서 가장 효율적으로 excited됨

Fluorescence Emission

- Emission maximum : Excitation과 유사하게 행동, fluorophore의 output은 특정 wavelength에서 가장 많이 발생

  ​

여기 해ㅐㅐ석 

*It's important to remember that although illumination at the excitation maximum of the fluorophore produces the greatest fluorescence output illumination at lower or higher wavelengths affects only the intensity of the emitted light the overall range and shape of the emission profile are unchanged.*

<br>

#### Flow Cytometer Basics

**Flow Cytometery Componets**

크게 세개의 중요한 부분으로 나누어짐 : *fluidics, optics, electronics*

Cytometry : measurement of physical or chemical characteristics of cells or particles

- 세포의 또는 입자의 물리적 혹은 화학적 특성 측정

Flow Cytometry : measurements are made as cells or particles in suspension pass individually through a flow cytometer instrument

- 유동 세포 계측법은 유동 세포 계측기를 통해 현탁액을 통과하는 세포 또는 입자로 개별적으로 측정됩니다.
- control, collection, separation of light에 의존
- Peformed on single cell suspensions??(*what is the cell suspention??* )
- Provides discrete measurements from each cell( 각 셀에서 개별 측정을 제공 )
- Provides a distribution of the measured characteristics( 측정된 특성의 분포를 제공 )

<br>

Flow Cytometry is a technology that simultaneously measures and analyses multiple characteristics of single particles as the flow in a fluid stream through a beam of light.

- 유동 세포 계측법 (Flow Cytometry)은 빛 입자를 통과하는 유체 흐름의 흐름으로서 단일 입자의 여러 특성을 동시에 측정하고 분석하는 기술입니다.


<br>

**Flow Cytometry의 장점**

- Records data from single cells  : 개별 세포들로부터 데이터를 기록
- Makes measurements on large numbers of cells : 많은 수의 세포를 측정가능
- Rich statistical analysis on cell populations : 세포 집단에 대한 풍부한 통계 분석 
- Because single cells are measured, it will reveal heterogeneity within a population
  - 왜냐하면 개별 세포가 측정되기 때문에, 이는 집단 내의 이질성을 드러낼 것이다. 
- Ability to multiplex - small sub-populations of cells can be identified
  - 다중화 능력 - 세포의 작은 부 집단이 식별될 수 있음(??)
- Thousands of cells can be analyzed rapidly : 수천 개의 세포를 빠르게 분석 가능
- Ideally suited for blood and other cells in suspension(현탁) : 현탁한 세포나 혈액에 이상적으로 적합함
- Ability to archive FCS(Flow Cytometry Standard) files, because of this Flexibility of data analysis give the ability to re-analyze data : 데이터 분석의 유연함으로 데이터를 재분석 할 수 있음 
- Using one of the more sophisticated flow cytometers, cells can be physically sorted. Sub-populations can be purified for further study.
- Using another of the more sophisticated flow cytometers, cells can be imaged at the same time, giving morphology and spatial information also.
  - 보다 정교한 flow cytometer를 사용해서 세포는 동시에 이미지화되어 형태학적인 공간 정보 또한 얻을 수 있음

<br>


- **Fluidics : 유체 시스템**
  - 흐르는 유체 내의 입자를 레이저 빔이 있는 곳까지 전달하는 역할
  - 대부분 형광물질을 낼 수 없기 때문에 유세포 분석을 위해 형광 표식 작업 필요 
  - sample is ingected into a stream of sheath fluid
  - 한번에 하나의 입자만이 레이저를 통과해야함
  - Particle Delivery 
    - Hydrodynamic Focusing - technique used to provide more accurate reusults from FC (https://en.wikipedia.org/wiki/Hydrodynamic_focusing)

      - 유체역학(fluid dynamics) 효과를 이용해 fluid 터널의 벽을 쌓음, wide한 튜브를 얇게 쓰는 방법? wall of fluid = sheath flow, 이 사이로 샘플이 주입됨

    - Acoustic Focusing = Better Precision, Precise Results at Any Collection Rate

      - core가 넓어도 상관 x, collection rate도 상관 x, faster than hydrodynamic
      - 음파를 사용하여 한줄로 광선을 통과하도록 함

  <br>

- **Optics : 광학 시스템**

  - light signal을 발생하고 수집
    - 흐르는 입자들을 발광시키는 빛을 발사하는 레이저들로 이루어짐

    - 입자에서 방출된 형광물질에 대한 데이터가 수집 => 입자별로 빛이 산란되는 고유의 특성을 기반으로 분석이 진행

    - Laser Light Scatter
        - Forward Scattered light(FSC) : 세포 표면적(cell-surface area) 또는 크기에 비례(proportional), 입자의 정확한 사이즈를 표현하는 것은 아님(rough estimate the size)
        - Side-Scattered light(SSC) :proportional to cell granularity/internal complexity of the cell. 셀 세분성 / 셀의 내부 복잡성에 비례합니다.  주로 레이저의 90도에서 수집

    - Optical Filters : 특정 파장 범위의 광을 선택적으로 투과 시키면서 나머지를 흡수 또는 반사

        종류 : Bandpass, Longpass, Shortpass, Dichronic, Neutral Density Filter

    - Multi-Laser System : 각각의 cell이 여러개의 레이저 iterrogation point를 지나감

    <br>

- **Electronics : 전자 시스템**
  - 감지된 빛 신호(optical signal)를 electronic pulses로 변환 후 감지하여 컴퓨터가 이를 데이터 형태로 분석할 수 있도록 함
  - 전류에 의해 Pulse가 생성 됨
  - Pulse의 진폭은 Photodetector에 도착하는 Photon의 수에 비례
    - Photodetector의 종류 :  Photo Diode, Photo Multiplier Tube(PMT)
    - Photo diode :  PMT 보다 less sensitive, strong한 신호를 detect, forward scatter signal
    - PMT : detect weaker singals generated by side scatter and by fluorescence
  - particle pass through the laser beam -> signal 생성
  - 빠른 시간에 많은 수의 세포에 대한 정보를 분석
  - 단일 매개변수 막대그래프 형태나 상호 매개변수의 그래프로 표시 => Cytogram


<br>

#### Data Basics

**Flow Cytometry Standard(FCS) Files**

- called "Listmode"

- 4 main segments : header(offsets), Text(keywords), Data(cell values), analysis(misc info)

  ​

**Histogram(Single parameter plot)**

- graphical representation  of single-parameter data and shows the relative number and distribution of events.


- x축 : signal intensity of the selected parameter 
- y축 : number of cells of events(count)



**Marker**

- Lines drawn around populations in order to distinguish them from other populations and to collect data on that population.
- Created histogram or another type of graph



똑같은 데이터를 Dot plot, density plot으로 나타낼 수 있음 

Dot Plot

- graphical representation of two-parm data where each axis represents the signal intensity of one parameter. 
- Each dot in the plot corresponds to one or more events detected above the threshold.



Density Plot

- graphical representation of two-param data where the color represent the collection of events with the same intensity 
- Each axis represents the signal intensity of one param.



Regions and Gate 

- commonly used in data analysis to identify diffeent subsets of populations in multi-color experiments

Regions

- Shapes or objects that are drawn arond a population of interest on one and two param plots.

Gate

- Process by which data is reduced by selecting populations with specific characteristics for display in one, rwo or three dimentions for further analysis.
  - 추가 분석을 위해서 1,2 또는 3차원으로 표시할 특정 특성을 가진집단을 선택하여 데이터를 줄이는 프로세스


- Defined when regions are used to iolate a specific group of cytometric events from a large set of data
  - Gates can be customized by using Boolean logic(OR, AND,NOT) to link multiple gates together
  - Most popular application is to use gates in sequential order to limit data display and define the para for statistical data display
