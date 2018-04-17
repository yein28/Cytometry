# Basic of flow(유) cytometry(세포측정), Part I: Gating and data analysis

http://kin.naver.com/open100/detail.nhn?d1id=11&dirId=1116&docId=1465825&qb=YWNvdXN0aWMgZm9jdXNpbmc=&enc=utf8&section=kin&rank=1&search_sort=0&spq=1&pid=TWU4NwpySDVssaCXKhZssssssmC-334949&sid=azAu9RSNOZQrTLN/hS76fA%3D%3D

-> 한글 자료..!!!

- 측정하고자 하는 세포집단의 세포들을 각각 하나씩 측정하여 분석하는 특징을 가짐 
- 유액 상태의 입자나 세포를 감지하기 위해 일정 파장을 띄는 형광이 표지된 항체 같은 형광염색소의 표지가 필수적, 형광을 감지 하기 위해 광원인 레이저 광원을 통한 형광의 발광 작용 이용



Fluorescence(형광, 발광) - 파장의 빛을 흡수하는 물질의 성질 

fluorophore is a molecule that is capable of fluorescing(fluoresce, 형광을 내다).

-> 형광물질(fluorophore)은 형광을 낼 수 있는 분자

ground state일때는 빛을 내지 않지만 외부에서 빛이 형광 분자를 hit 하면 분자는 빛 에너지를 흡수할 수 있음 

이 프로세스를 "excitation"이라고 함

the fluorophore가 high-energy configuration 일때는 unstable하기때문에 결국 lowest-energy excited state를 취합니다.semi-stable이라고 부르는

fluorophore가 excited states에 있는 시간을 excited lifetime이라고함, 굉장히 짧게 지속됨

fluorophore가 semi-stable excites state에서 rearrage함, ground state로 그리고 과잉된 에너지가 빛으로 방출됨

방출 된 광은 흡수 된 광보다 에너지가 낮고 따라서 장파장이다. 방출되는 빛의 색이 흡수된 빛의 색과 다르다는 것을 의미함



Absorbed light(Absorption) -> Excitation -> Loss of Energy -> Emission(Emitted light)



Excitation Range(Spectrum) - 특정 파장 범위의 에너지의 흡수

Emission Range(Spectrum) - 다른 특정 파장 범위의 에너지로 재방출 



요약

- Fluorohpore는 분자, 빛 에너지를 흡수할때 excited 상태에 도달할 수 있고, 빛 에너지를 방출하는 
- excitation, excited lifetime, emission의 세가지 프로세스는 fluorescence(형광발광)이라고 람
- excitation과 emission 파장이 다르면, 흡수되거나 방출된 light는 가시 스펙트럼 상의 다른색 또는 영역으로써 검출 가능함

  ​

*Result of process in certain molecules which are called fluorophores, or fluorescent dyes.*

fluorophores또는 형광 염료라고하는 특정분자의 process의 결과를 형광이라고합니다.

*A fluorescent compound absorbs light, which causes an electron in the compound to be raised to a higher energy level.*

형광 화합물은 화합물 내의 전자를 높은 에너지 레벨로 상승 시키는 빛을 흡수합니다.

*The  excited electron quickly decays, emitting excess energy as a photon of light.*

excited된 전자는 빠르게 붕괴되고, 과도한 에너지를 빛의 광자로 방출합니다.

*The emitted light is called fluorescence.* 

방출된 빛을 형광이라고 합니다. 

- Absorption(흡수, 통합) spectrum : The wave length range over which a flouorescent compound can be excited.

- Emission(빛,열, 가스등의 배출) spectrum : The range or emitted wavelengths of a flouorescent compound, it is a longer wavelenth than the absorption wavelengths.

- Stokes Shift : difference between the excitation and emission wavelengths

  ​			excitation과 emission wavelength 사이의 차이

A flouorescent probe is a fluorophore designed to localize within a specific refion o f a cell or respond to a specific stimulus.



Flow Cytometery Componets

크게 세개의 중요한 부분으로 나누어짐 : fludics, optics, electronics

Cytometry : measurement of physical or chemical characteristics of cells or particles

- 세포의 또는 입자의 물리적 혹은 화학적 특성 측정

Flow Cytometry : measurements are made as cells or particles in suspension pass individually through a flow cytometer instrument

- 유동 세포 계측법은 유동 세포 계측기를 통해 현탁액을 통과하는 세포 또는 입자로 개별적으로 측정됩니다.
- control, collection, separation of light에 의존

*what is the cell suspention??* 

- Peformed on single cell suspensions??
- provides discrete measurements from each cell( 각 셀에서 개별 측정을 제공 )
- provides a distribution of the measured characteristics( 측정된 특성의 분포를 제공 )



Flow Cytometry is a technology that simultaneously measures and analyses multiple characteristics of single particles as the flow in a fluid stream through a beam of light.

- 유동 세포 계측법 (Flow Cytometry)은 빛 입자를 통과하는 유체 흐름의 흐름으로서 단일 입자의 여러 특성을 동시에 측정하고 분석하는 기술입니다.



- Fluidics : 유체 시스템
  - 흐르는 유체 내의 입자를 레이저 빔이 있는 곳까지 전달하는 역할
  - 대부분 형광물질을 낼 수 없기 때문에 유세포 분석을 위해 형광 표식 작업 필요 
  - sample is ingected into a stream of sheath fluid(???)
  - 한번에 하나의 입자만이 레이저를 통과해야함
  - Particle Delivery 
    - Hydrodynamic Focusing - technique used to provide more accurate reusults from FC (https://en.wikipedia.org/wiki/Hydrodynamic_focusing)

      - 유체역학(fluid dynamics) 효과를 이용해 fluid 터널의 벽을 쌓음, wide한 튜브를 얇게 쓰는 방법? wall of fluid = sheath flow, 이 사이로 샘플이 주입됨

    - Acoustic Focusing = Better Precision, Precise Results at Any Collection Rate

      - core가 넓어도 상관 x, collection rate도 상관 x, faster than hydrodynamic

      - 음파를 사용하여 한줄로 광선을 통과하도록 함

        ​

- Optics : 광학 시스템

  - light signal을 발생하고 수집
    - 흐르는 입자들을 발광시키는 빛을 발사하는 레이저들로 이루어짐

    - 입자에서 방출된 형광물질에 대한 데이터가 수집 => 입자별로 빛이 산란되는 고유의 특성을 기반으로 분석이 진행

    - Laser Light Scatter
        - Forward Scattered light(FSC) : 세포 표면적(cell-surface area) 또는 크기에 비례(proportional), 입자의 정확한 사이즈를 표현하는 것은 아님(rough estimate the size)
        - Side-Scattered light(SSC) :proportional to cell granularity/internal complexity of the cell. 셀 세분성 / 셀의 내부 복잡성에 비례합니다.  주로 레이저의 90도에서 수집

    - Optical Filters : 특정 파장 범위의 광을 선택적으로 투과 시키면서 나머지를 흡수 또는 반사, 종류 : Bandpass, Longpass, Shortpass,Dichronic,Neutral Density Filter

        ​

- Electronics : 전자 시스템
  - 감지된 빛 신호(optical signal)를 electronic pulses로 변환 후 감지하여 컴퓨터가 이를 데이터 형태로 분석할 수 있도록 함
  - 전류에 의해 Pulse가 생성 됨
  - Pulse의 진폭은 Photodetector에 도착하는 Photon의 수에 비례
  - particle pass through the laser beam 할때 signal 생성
  - 빠른 시간에 많은 수의 세포에 대한 정보를 분석
  - 단일 매개변수 막대그래프 형태나 상호 매개변수의 그래프로 표시 => Cytogram




Data Basics

Flow Cytometry Standard(FCS) Files()

- called "Listmode" 4 main segments, header, Text, Data, analysis

  ​

Histogram : graphical representation  of single-parameter data and shows the relative number and distribution of events.

- x축 : signal intensity of the selected parameter 

- y축 : number of events(count)

  ​

 Marker

- Lines drawn around populations in order to distinguish them from other populations and to collect data on that population
- created histogram or another type of graph

Dot Plot

- graphical representation of two-parm data where each axis represents the signal intensity of one parameter. 
- Each dot in the plot corresponds to one or more events detected above the threshold.

Density Plot

- graphical representation of two-param data where the color represent the collection of ebents with the same intensity 
- Each axis represents the signal intensity of one param.

똑같은 데이터를 Dot plot, density plot으로 나타낼 수 있음 



Regions and Gate 

- commonly used in data analysis to identify diffeent subsets of populations in multi-color experiments

Regions

- Shapes or objects that are drawn arond a population of interest on one and two param plots.

Gate

- Defined when regions are used to iolate a specific group of cytometric events from a large set of data
  - Gates can be customized by using Boolean logic(OR, AND,NOT) to link multiple gates together
  - Most popular application is to use gates in sequential order to limit data display and define the para for statistical data display

Statistics