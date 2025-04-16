`input/pagecontent/guidance.md`

### Guidance

This section provides more detailed background and guidance on the use that can be made of a digital protocol in FHIR and the mechanics of translating your existing protocol into FHIR.

# 1    Context and Core Objectives

Having the protocol for a clinical study in digital format is an enabling step for a wide range of transformations to processes for authoring, approving, executing and reporting studies. Some examples are shown in Figure 1: Potential developments enabled by a Digital Protocol.

<div><img src="image-20250415140641414.png" alt="image-20250415140641414.png" style="max-width: 80%;
 height: auto;" />
<p>Figure 1: Potential developments enabled by a Digital Protocol</p></div>

This Implementation Guide gives general guidance on the creation in FHIR format of a digital representation of a protocol for a clinical study. It shows how the placement of data items within the FHIR format is derived from the USDM data model and also shows how the sections of the M11 CeSHarP specification are represented within the FHIR structures.

## 1.1   Background

There are three original sets of work that have been brought together to develop this IG. 

**ICH M11 CeSHarP** – is establishing a framework for clinical study protocols so that information is presented consistently always using the same headings and the same sequence within the document. Having a familiar structure promotes efficient review and reduces the risks of significant elements being overlooked. This “document” may be a paper format but is expected to be in a machine readable format and hence avoiding information being “trapped” in a document and requiring manual reentry. There can be sevral different formats at machine readable level and ICH want one such format to be FHIR based and this requirement is the genesis of this IG. The primary use case that ICH are concerned with is the transfer of a protocol from a sponsor to a regulator (XREF: Sponsor to Regulator Use Case)

**CDISC USDM** – This is joint work between CDISC and TransCelerate aimed at providing an information model that defines all the data elements required to specify a study protocol. The primary use case here is to provide a representation of a protocol that can be used during the design, definition and startup of a study. (XREF: Protocol Definition during design and submission)

Question[[HG1\]](#_msocom_1) 

**Vulcan Schedule of Activities** – This is work that began in PHUSE and transitioned into a Vulcan project. This provides a representation in FHIR of the schedule of activities that is a key part of most protocols. The use case here is focused on having an unambiguous SoA definition during execution of a study that can for example be used to generate a detailed care plan for a specific patient. (XREF: Protocol Use during study execution)

More detailed background and links to source material for each of these projects can be found in (XREF Support:4. Other Links)

------



 [[HG1\]](#_msoanchor_1)Do we need to talk more about DDF
