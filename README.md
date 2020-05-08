# Persistent Identifiers

An identifier is any label used to name some thing (person, place, event) uniquely (whether online or offline).  URLs are an example of an identifier. So are serial numbers, and personal names. A persistent identifier is guaranteed to be managed and kept up to date over a defined time period to reliably point to a digital or physical entity

## Feature PID

http://www.linked.data.gov.au/feature/qld/[prefix][feature_id]

Where prefixes are:

    pr - Province
    sp - Sub Province
    og - Orogen
    cr - Craton
    dn - Depression
    bn - Basin
    tr - Trough

## Site PID

http://www.linked.data.gov.au/site/qld/[prefix][site_id]

Where prefixes are:

    bh - borehole
    mo - mineral occurrence
    mi - mine
    oc - outcrop

## Survey PID

http://www.linked.data.gov.au/survey/qld/[prefix][survey_id]

Where prefixes are (business to review):

    ds - directional
    el - electrical
    em - electromagnetic
    gc - geochemistry
    gt - geotechnical
    ge - geothermics
    gv - gravity
    hy - hydrochemistry
    mg - magnetic
    mt - magnetotelluric
    pp - petrophysical
    ph - photographic
    pg - physical-geology
    ps - process
    rm - radiometric
    ss - seismic
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

    rc - rockchip
    wr - whole rock
    ss - stream sediments
    sl - soil

More prefixes to come as vocab is developed.

## Observation PID

http://www.linked.data.gov.au/observation/qld/[prefix][observation_id]

Prefix will align to observation type, e.g. Hylogging = hy

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
