# Persistent Identifiers

An identifier is any label used to name some thing (person, place, event) uniquely (whether online or offline).  URLs are an example of an identifier. So are serial numbers, and personal names. A persistent identifier is guaranteed to be managed and kept up to date over a defined time period to reliably point to a digital or physical entity

## Reports use their own prefix

Reports will have their own prefix e.g. https://geoscience.data.qld.gov.au/report/cr12345  
For reports migrated from QDEX Reports, we add the `cr` prefix to the existing report number from QDEX Reports.

    cr - Report

## Feature PID

http://www.linked.data.gov.au/feature/qld/[prefix][feature_id]

Where prefixes are:

    gfabz - AbundanceZone
    gfanc - AncientContinent
    gfann - Anticline
    gfanm - Anticlinorium
    gfant - Antiform
    gfank - AntiformalStack
    gfarh - Arch
    gfasz - AssemblageZone
    gfasn - AssociationZone
    gfbed - Bed
    gfbds - Beds
    gfbst - BiostratigraphicUnit
    gfblk - Block
    gfcht - ChronostratigraphicUnit
    gfcmx - Complex
    gfcrz - ConcurrentRangeZone
    gfcnt - Continent
    gfcrn - Craton
    gfcrt - CrustalElement
    gfdnf - DenudationalFeature
    gfdpn - Depression
    gfdme - Dome
    gfdpx - Duplex
    gfeby - Embayment
    gfecp - Escarpment
    gfxcp - ExtendedCrustProvince
    gfflt - Fault
    gfflp - FaultScarp
    gffts - FaultSet
    gfflm - FaultSystem
    gfflz - FaultZone
    gfflw - Flow
    gffld - Fold
    gffdb - FoldBelt
    gffrm - Formation
    gfgra - GeoResourceAccumulation
    gfghs - GeologicalHeritageSite
    gfgss - GeologicallySignificantSite
    gfgpk - Geopark
    gfgpd - GeophysicalDomain
    gfgpf - GeophysicalFeature
    gfgtl - Geotrail
    gfgbn - Graben
    gfgrp - Group
    gfhgn - HalfGraben
    gfhrt - Horst
    gfigp - IgneousProvince
    gfinl - Inlier
    gfinz - IntervalZone
    gfklp - Klippe
    gflip - LargeIgneousProvince
    gflnz - LineageZone
    gfltd - Lithodeme
    gfldf - LithodemicFeature
    gflsu - LithostratigraphicUnit
    gfmpb - MagnetostratigraphicPolaritySubzone
    gfmpp - MagnetostratigraphicPolaritySuperzone
    gfmpz - MagnetostratigraphicPolarityZone
    gfmsu - MagnetostratigraphicUnit
    gfmbr - Member
    gfmnp - MineralProvince
    gfmnc - Monocline
    gfmyz - MyloniteZone
    gfnpp - Nappe
    gfnpx - NappeComplex
    gforn - Orogen
    gforg - OrogenicCollage
    gfout - Outlier
    gfofz - OverturnedFold
    gfpdu - PedostratigraphicUnit
    gfpnn - Peneplain
    gfprc - PresentContinent
    gfrnz - RangeZone
    gfrdg - Ridge
    gfsdb - SedimentaryBasin
    gfssp - SeismicProvince
    gfsqu - SequenceStratigraphicUnit
    gfshz - ShearZone
    gfshd - Shield
    gfste - StratigraphicEvent
    gfstf - StratigraphicFeature
    gfstu - StratigraphicUnit
    gfstr - StructuralFeature
    gfsbn - Subbasin
    gfsbg - Subgroup
    gfsut - Suite
    gfspb - Superbasin
    gfspc - Supercontinent
    gfspn - Supercraton
    gfspg - Supergroup
    gfsps - Supersuite
    gfsyn - Syncline
    gfsyc - Synclinorium
    gfsyf - Synform
    gftrz - TaxonRangeZone
    gftse - tectonostratigraphicEntity
    gftey - TectonicEntity
    gftcr - TectonicFeature
    gfplt - TectonicPlate
    gftmp - TectonisedMetomorphosedProvince
    gftrn - Terrane
    gftrh - Trough
    gfunc - Unconformity
    gfwnw - Window

*note: Administrative features (i.e. Resource Permits use thier abbreviation such as PL for Petroleum Lease)


## Site PID

http://www.linked.data.gov.au/site/qld/[prefix][site_id]

Where prefixes are:

    au - auger
    bs - base-station
    bh - borehole
    ct - cutting
    fs - field-site
    av - alluvial
    wc - watercourse
    bc - beach
    wy - waterbody
    cv - colluvial
    oc - outcrop
    sc - subcrop
    rg - regolith
    pd - pedolith
    sr - saprolith
    tl - tailings
    sl - spoil
    mi - mine
    om - open-cut-mine
    ug - underground-mine
    qy - quarry
    pt - pit
    pj - project-site
    th - trench
    wb - wellbore
    uk - unknown


## Survey PID

http://www.linked.data.gov.au/survey/qld/[prefix][survey_id]

Where prefixes are (business to review):

    at - atmospheric
    gc - geochemistry
    gp - geophysical
    gt - geotechnical
    hy - hydrochemistry
    pp - petrophysical
    pg - physical-geology
    ss - seismic
    st - spatial
    sp - spectral

## Geophysical Survey PIDs in Geoproperties

Aerial and Ground geophysics recorded in Geoproperties will use the following PID prefixes:

    ag - aerial geophysics survey
    gs - ground geophysics survey

When the survey is exported out of Geoproperties to the Open Data Portal, the CKAN PID is created from the Observation Type.

As an example:

* Aerial gephysics survey AG1400 contained a magnetic and a radiometric survery.
* An ODP magnetic survey dataset is created where Survey Title = AG1400 and Survey PID = MG1400
* An ODP radiometric survey dataset is created where Survey Title = AG1400 and Survey PID = RM1400

This process applies to the following survey types:

    el - electrical
    em - electromagnetic
    gv - gravity
    gg - gravity-gradiometry
    mg - magnetic
    mt - magnetotelluric
    rm - radiometric

Note that this does not apply to seismic surveys, which are a type of ground geophysical survey.

## Sample PID

http://www.linked.data.gov.au/sample/qld/[prefix][sample_id]

Where prefixes are:

    IMLG - image-log
    BLSAMP - blasted-sample
    BHCM - borehole-cement
    BCL - bulk-cyanide-leach-sample
    CSAMP - channel-sample
    CCO - composited-core
    CCU - composited-cuttings
    CCSAMP - continuous-channel-sample
    CORE - core
    PLUG - core-plug
    CRUSH - crushed-rock
    CUT - cuttings
    DVLG - deviation-log
    DLFD - drill-fluid
    DSPOIN - drill-spoil
    DSTEM - drill-stem-test
    FWSAMP - feather-and-wedge-sample
    FLOAT - float
    HAND - hand-sample
    HYSN - hyperspectral-scan
    MACFOS - macrofossil
    MICFOS - microfossil
    ORE - ore-sample
    ORIENT - oriented-or-orientation-sample
    OSAMP - oriented-sample
    PMAG - palaeomagnetic-sample
    PCON - pan-concentrate
    PHGR - photograph
    PBLK - polished-block
    PCHIP - powdered-chip
    RDSAMP - random-dump-sample
    RSAMP - random-sample
    CHIP - rock-chips
    SCREE - scree
    SDSAMP - selected-dump-sample
    SEL - selected-sample
    SWC - side-wall-core
    SSS - sieved-stream-sediment-sample
    SHSAMP - sledge-hammer-sample
    SOIL - soil-sample
    STRSED - stream-sediment-sample
    SUSP - suspended-silt-sample
    TMOUND - termite-mound
    TSPOIL - trench-spoil
    UNSP - unspecified
    VIDO - video
    WTRS - water-specimen
    WHEAD - wellhead
    PETL - petrophysical-log

More prefixes to come as vocab is developed.

## Observation PID

http://www.linked.data.gov.au/observation/qld/[prefix][observation_id]

    ALTN - alteration
    AUGR - auger-hole-description
    CMNT - cement-int
    CSPR - coal-seam-properties
    COAL - coal-type
    COHR - coherance
    DSUP - depths-of-supergene-alteration
    DRCT - directional
    DRLL - drilling-int
    DRFD - drill-fluid-int
    EL - electrical
    EM - electromagnetic
    FABR - fabric
    FOSS - fossils
    GEOC - geochemical-signature
    GE - geothermics
    GV - gravity
    GG - gravity-gradiometry
    HYPR - hyperspectral
    IGST - igneous-structures
    SEQU - internal-sequences
    LITH - lith-int
    MG - magnetic
    MY - magnetic-gradiometry
    MT - magnetotelluric
    METS - metamorphic-structures
    METTYP - metamorphic-type
    META - metamorphism
    DEXP - mineral-deposit-expression
    DFRM - mineral-deposit-form
    COMPON - mineralogical-components
    MISC - miscellaneous-observation
    MULT - multispectral
    OTEX - ore-textures
    PANC - panchromatic
    PERF - perf-int
    PHOT - photographic
    PHYS - physical
    PSTN - positional
    QTEX - quartz-textures
    RM - radiometric
    REGO - regolith-observations
    RSVR - reservoir-int
    RCLASS - rock-classification
    SEDFAC - sedimentary-lithofacies
    SEDS - sedimentary-structures
    2d - seismic-2d
    3d - seismic-3d
    4d - seismic-4d
    STRT - strat-int
    TCST - tectonic-structures
    TEXT - textures
    TBLR - tubular-int
    VELS - velocity-survey
    WETH - weathering-features
    WCPI - well-completion-int
    YOUNG - younging

More prefixes to come as vocab is developed.

## Result

http://www.linked.data.gov.au/result/qld/[result_id]

No prefix

## Geological property

http://www.linked.data.gov.au/geoproperty/qld/[geoproperty_id]

No prefix


## IGSN Minting

## See also:
[Persistent identifiers: awareness level](https://www.ands.org.au/guides/persistent-identifiers-awareness)  
[Persistent identifiers: working level](https://www.ands.org.au/guides/persistent-identifiers-working)

## Licence
The content of this repository is licensed for use with the [Creative Commons 4.0 License](https://creativecommons.org/licenses/by/4.0/). See the [license deed](LICENSE) for details.


## Contacts 
*owner*:  
**Mark Gordon**  
*Director - Geoscience Information*  
Geological Survey of Queensland  
<mark.gordon@dnrme.qld.gov.au>  

*author*:  
**David Crosswell**  
*Enterprise Architect*  
CrossLateral  
<https://crosslateral.com.au>
