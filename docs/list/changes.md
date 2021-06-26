# Additions and changes Darwin Core terms

Title
: Additions and changes to Darwin Core terms

Date version issued
: 2021-06-25

Creator
: TDWG Darwin Core Maintenance Group

## 1 Introduction (Informative)

This document contains terms that were changed or added and will become part of the most recent version of the Darwin Core vocabulary.

**Note:** The Executive Decisions field for these terms will be updated following ratification.

### 1.1 Status of the content of this document

The values of the `Term IRI` and `Definition` are normative. The values of `Term Name` are non-normative, although one can expect that the namespace abbreviation prefix is one commonly used for the term namespace.  `Label` and the values of all other properties (such as `Examples` and `Notes`) are non-normative.

### 1.2 RFC 2119 key words
The key words "MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD", "SHOULD NOT", "RECOMMENDED", "MAY", and "OPTIONAL" in this document are to be interpreted as described in [RFC 2119](https://tools.ietf.org/html/rfc2119).

### 1.3 Namespace abbreviations

The following namespace abbreviations are used in this document:

| abbreviation | IRI |
| --- | --- |
| dwc: | http://rs.tdwg.org/dwc/terms/ |
| dwciri: | http://rs.tdwg.org/dwc/iri/ |
| dc: | http://purl.org/dc/elements/1.1/ |
| dcterms: | http://purl.org/dc/terms/ |

## 2 Use of Terms

Due to the requirements of [Section 1.4.3 of the Darwin Core RDF Guide](../rdf/#143-use-of-darwin-core-terms-in-rdf-normative), terms in the `dwciri:` namespace MUST be used with IRI values. Terms in the `dwc:` and `dc:` namespaces are generally expected to have string literal values. Values for terms in the `dcterms:` namespace will depend on the details of the term. See [Section 3 of the Darwin Core RDF Guide](../rdf/#3-term-reference-normative) for details.

## 3 Indices (omitted)

## 4 Vocabulary
<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_acceptedNameUsage"></a>Term Name  dwc:acceptedNameUsage</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/acceptedNameUsage">http://rs.tdwg.org/dwc/terms/acceptedNameUsage</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/acceptedNameUsage-2021-06-25">http://rs.tdwg.org/dwc/terms/version/acceptedNameUsage-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Accepted Name Usage</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The full name, with authorship and date information if known, of the currently valid (zoological) or accepted (botanical) taxon.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>The full scientific name, with authorship and date information if known, of the accepted (botanical) or valid (zoological) name in cases where the provided scientificName is considered by the reference indicated in the accordingTo property, or of the content provider, to be a synonym or misapplied name. When applied to an Organism or Occurrence, this term should be used in cases where a content provider regards the provided scientificName to be inconsistent with the taxonomic perspective of the content provider. For example, there are many discrepancies within specimen collections and observation datasets between the recorded name (e.g., the most recent identification from an expert who examined a specimen, or a field identification for an observed organism), and the name asserted by the content provider to be taxonomically accepted.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`Tamias minimus` (valid name for Eutamias minimus).</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_acceptedNameUsageID"></a>Term Name  dwc:acceptedNameUsageID</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/acceptedNameUsageID">http://rs.tdwg.org/dwc/terms/acceptedNameUsageID</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/acceptedNameUsageID-2021-06-25">http://rs.tdwg.org/dwc/terms/version/acceptedNameUsageID-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Accepted Name Usage ID</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>An identifier for the name usage (documented meaning of the name according to a source) of the currently valid (zoological) or accepted (botanical) taxon.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>This term should be used for synonyms or misapplied names to refer to the taxonID of a Taxon record that represents the accepted (botanical) or valid (zoological) name. For Darwin Core Archives the related record should be present locally in the same archive.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`tsn:41107` (ITIS), `urn:lsid:ipni.org:names:320035-2` (IPNI), `2704179` (GBIF), `6W3C4` (COL)</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_associatedOccurrences"></a>Term Name  dwc:associatedOccurrences</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/associatedOccurrences">http://rs.tdwg.org/dwc/terms/associatedOccurrences</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/associatedOccurrences-2021-06-25">http://rs.tdwg.org/dwc/terms/version/associatedOccurrences-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Associated Occurrences</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>A list (concatenated and separated) of identifiers of other Occurrence records and their associations to this Occurrence.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>This term can be used to provide a list of associations to other Occurrences. Note that the ResourceRelationship class is an alternative means of representing associations, and with more detail. Recommended best practice is to separate the values in a list with space vertical bar space ( | ).</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`"parasite collected from":"<a href="https://arctos.database.museum/guid/MSB:Mamm:215895?seid=950760">https://arctos.database.museum/guid/MSB:Mamm:215895?seid=950760</a>"`, `"encounter previous to":"<a href="http://arctos.database.museum/guid/MSB:Mamm:292063?seid=3175067">http://arctos.database.museum/guid/MSB:Mamm:292063?seid=3175067</a>" | "encounter previous to":"<a href="http://arctos.database.museum/guid/MSB:Mamm:292063?seid=3177393">http://arctos.database.museum/guid/MSB:Mamm:292063?seid=3177393</a>" | "encounter previous to":"<a href="http://arctos.database.museum/guid/MSB:Mamm:292063?seid=3177394">http://arctos.database.museum/guid/MSB:Mamm:292063?seid=3177394</a>" | "encounter previous to":"<a href="http://arctos.database.museum/guid/MSB:Mamm:292063?seid=3177392">http://arctos.database.museum/guid/MSB:Mamm:292063?seid=3177392</a>" | "encounter previous to":"<a href="http://arctos.database.museum/guid/MSB:Mamm:292063?seid=3609139">http://arctos.database.museum/guid/MSB:Mamm:292063?seid=3609139</a>"`</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>DataSets/DataSet/Units/Unit/Associations/UnitAssociation/AssociatedUnitSourceInstitutionCode + DataSets/DataSet/Units/Unit/Associations/UnitAssociation/AssociatedUnitSourceName + DataSets/DataSet/Units/Unit/Associations/UnitAssociation/AssociatedUnitID</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2014-10-26_14">http://rs.tdwg.org/decisions/decision-2014-10-26_14</a></td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2014-10-30_16">http://rs.tdwg.org/decisions/decision-2014-10-30_16</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_associatedOrganisms"></a>Term Name  dwc:associatedOrganisms</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/associatedOrganisms">http://rs.tdwg.org/dwc/terms/associatedOrganisms</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/associatedOrganisms-2021-06-25">http://rs.tdwg.org/dwc/terms/version/associatedOrganisms-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Associated Organisms</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>A list (concatenated and separated) of identifiers of other Organisms and the associations of this Organism to each of them.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>This term can be used to provide a list of associations to other Organisms. Note that the ResourceRelationship class is an alternative means of representing associations, and with more detail. Recommended best practice is to separate the values in a list with space vertical bar space ( | ).</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`"sibling of":"<a href="http://arctos.database.museum/guid/DMNS:Mamm:14171">http://arctos.database.museum/guid/DMNS:Mamm:14171</a>"`, `"parent of":"<a href="http://arctos.database.museum/guid/MSB:Mamm:196208">http://arctos.database.museum/guid/MSB:Mamm:196208</a>" | "parent of":"<a href="http://arctos.database.museum/guid/MSB:Mamm:196523">http://arctos.database.museum/guid/MSB:Mamm:196523</a>" | "sibling of":"<a href="http://arctos.database.museum/guid/MSB:Mamm:142638">http://arctos.database.museum/guid/MSB:Mamm:142638</a>"`</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2014-10-26_14">http://rs.tdwg.org/decisions/decision-2014-10-26_14</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_associatedReferences"></a>Term Name  dwc:associatedReferences</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/associatedReferences">http://rs.tdwg.org/dwc/terms/associatedReferences</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/associatedReferences-2021-06-25">http://rs.tdwg.org/dwc/terms/version/associatedReferences-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Associated References</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>A list (concatenated and separated) of identifiers (publication, bibliographic reference, global unique identifier, URI) of literature associated with the Occurrence.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Recommended best practice is to separate the values in a list with space vertical bar space ( | ). Note that the ResourceRelationship class is an alternative means of representing associations, and with more detail. Note also that the intended usage of the term dcterms:references in Darwin Core when applied to an Occurrence is to point to the definitive source representation of that Occurrence if one is available. Note also that the intended usage of dcterms:bibliographicCitation in Darwin Core when applied to an Occurrence is to provide the preferred way to cite the Occurrence itself.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`<a href="http://www.sciencemag.org/cgi/content/abstract/322/5899/261`">http://www.sciencemag.org/cgi/content/abstract/322/5899/261`</a>, `Christopher J. Conroy, Jennifer L. Neuwald. 2008. Phylogeographic study of the California vole, Microtus californicus Journal of Mammalogy, 89(3):755-767.`, `Steven R. Hoofer and Ronald A. Van Den Bussche. 2001. Phylogenetic Relationships of Plecotine Bats and Allies Based on Mitochondrial Ribosomal Sequences. Journal of Mammalogy 82(1):131-137. | Walker, Faith M., Jeffrey T. Foster, Kevin P. Drees, Carol L. Chambers. 2014. Spotted bat (Euderma maculatum) microsatellite discovery using illumina sequencing. Conservation Genetics Resources.`</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>DataSets/DataSet/Units/Unit/UnitReferences</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2014-10-30_16">http://rs.tdwg.org/decisions/decision-2014-10-30_16</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_associatedTaxa"></a>Term Name  dwc:associatedTaxa</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/associatedTaxa">http://rs.tdwg.org/dwc/terms/associatedTaxa</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/associatedTaxa-2021-06-25">http://rs.tdwg.org/dwc/terms/version/associatedTaxa-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Associated Taxa</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>A list (concatenated and separated) of identifiers or names of taxa and the associations of this Occurrence to each of them.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>This term can be used to provide a list of associations to Taxa other than the one defined in the Occurrence. Note that the ResourceRelationship class is an alternative means of representing associations, and with more detail. This term is not apt for establishing relationships between Taxa, only between specific Occurrences of an Organism with other Taxa. Recommended best practice is to separate the values in a list with space vertical bar space ( | ).</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`"host":"Quercus alba"`, `"host":"gbif.org/species/2879737"`,`"parasitoid of":"Cyclocephala signaticollis" | "predator of":"Apis mellifera"`</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>DataSets/DataSet/Units/Unit/Gathering/Synecology/AssociatedTaxa</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2014-10-30_16">http://rs.tdwg.org/decisions/decision-2014-10-30_16</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_basisOfRecord"></a>Term Name  dwc:basisOfRecord</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/basisOfRecord">http://rs.tdwg.org/dwc/terms/basisOfRecord</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/basisOfRecord-2021-06-25">http://rs.tdwg.org/dwc/terms/version/basisOfRecord-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Basis of Record</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The specific nature of the data record.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Recommended best practice is to use the standard label of one of the Darwin Core classes.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`PreservedSpecimen`, `FossilSpecimen`, `LivingSpecimen`, `MaterialSample`, `Event`, `HumanObservation`, `MachineObservation`, `Taxon`, `Occurrence`, `MaterialCitation`</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>DataSets/DataSet/Units/Unit/RecordBasis</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2009-12-07_2">http://rs.tdwg.org/decisions/decision-2009-12-07_2</a></td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2014-10-26_15">http://rs.tdwg.org/decisions/decision-2014-10-26_15</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dcterms_bibliographicCitation"></a>Term Name  dcterms:bibliographicCitation</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://purl.org/dc/terms/bibliographicCitation">http://purl.org/dc/terms/bibliographicCitation</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://dublincore.org/usage/terms/history/#bibliographicCitation-002">http://dublincore.org/usage/terms/history/#bibliographicCitation-002</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Bibliographic Citation</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>A bibliographic reference for the resource.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>From Dublin Core, "Recommended practice is to include sufficient bibliographic detail to identify the resource as unambiguously as possible." The intended usage of this term in Darwin Core is to provide the preferred way to cite the resource itself - "how to cite this record". Note that the intended usage of dcterms:references in Darwin Core, by contrast, is to point to the definitive source representation of the resource - "where to find the as-close-to-original reference, if one is available.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>Occurrence example: `Museum of Vertebrate Zoology, UC Berkeley. MVZ Mammal Collection (Arctos). Record ID: <a href="http://arctos.database.museum/guid/MVZ:Mamm:165861?seid=101356">http://arctos.database.museum/guid/MVZ:Mamm:165861?seid=101356</a>. Source: <a href="http://ipt.vertnet.org:8080/ipt/resource.do?r=mvz_mammal.`">http://ipt.vertnet.org:8080/ipt/resource.do?r=mvz_mammal.`</a> Taxon example: `<a href="https://www.gbif.org/species/2439608">https://www.gbif.org/species/2439608</a> Source: GBIF Taxonomic Backbone`, Event example: `Rand, K.M., Logerwell, E.A. The first demersal trawl survey of benthic fish and invertebrates in the Beaufort Sea since the late 1970s. Polar Biol 34, 475–488 (2011). <a href="https://doi.org/10.1007/s00300-010-0900-2`">https://doi.org/10.1007/s00300-010-0900-2`</a></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_coordinateUncertaintyInMeters"></a>Term Name  dwc:coordinateUncertaintyInMeters</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/coordinateUncertaintyInMeters">http://rs.tdwg.org/dwc/terms/coordinateUncertaintyInMeters</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/coordinateUncertaintyInMeters-2021-06-25">http://rs.tdwg.org/dwc/terms/version/coordinateUncertaintyInMeters-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Coordinate Uncertainty In Meters</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The horizontal distance (in meters) from the given decimalLatitude and decimalLongitude describing the smallest circle containing the whole of the Location. Leave the value empty if the uncertainty is unknown, cannot be estimated, or is not applicable (because there are no coordinates). Zero is not a valid value for this term.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`30` (reasonable lower limit on or after 2020-05-01 of a GPS reading under good conditions if the actual precision was not recorded at the time). `100` (reasonable lower limit before 2020-05-01 of a GPS reading under good conditions if the actual precision was not recorded at the time). `71` (uncertainty for a UTM coordinate having 100 meter precision and a known spatial reference system).</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>DataSets/DataSet/Units/Unit/Gathering/SiteCoordinateSets/SiteCoordinates/CoordinatesLatLon/CoordinateErrorDistanceInMeters</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_country"></a>Term Name  dwc:country</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/country">http://rs.tdwg.org/dwc/terms/country</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/country-2021-06-25">http://rs.tdwg.org/dwc/terms/version/country-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Country</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The name of the country or major administrative unit in which the Location occurs.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Recommended best practice is to use a controlled vocabulary such as the Getty Thesaurus of Geographic Names. Recommended best practice is to leave this field blank if the Location spans multiple entities at this administrative level or if the Location might be in one or another of multiple possible entities at this level. Multiplicity and uncertainty of the geographic entity can be captured either in the term higherGeography or in the term locality, or both.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`Denmark`, `Colombia`, `España`</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>DataSets/DataSet/Units/Unit/Gathering/Country/Name</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_cultivarEpithet"></a>Term Name  dwc:cultivarEpithet</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/cultivarEpithet">http://rs.tdwg.org/dwc/terms/cultivarEpithet</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/cultivarEpithet-2021-06-25">http://rs.tdwg.org/dwc/terms/version/cultivarEpithet-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Cultivar Epithet</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>Part of the name of a cultivar, cultivar group or grex that follows the scientific name.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>According to the Rules of the Cultivated Plant Code, a cultivar name consists of a botanical name followed by a cultivar epithet. The value given as the cultivarEpithet should exclude any quotes. The term taxonRank should be used to indicate which type of cultivated plant name (e.g. cultivar, cultivar group, grex) is concerned. This epithet, including any enclosing apostrophes or suffix, should be provided in scientificName as well.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`King Edward` (for scientificName "Solanum tuberosum 'King Edward'" and taxonRank "cultivar"); `Mishmiense` (for scientificName "Rhododendron boothii Mishmiense Group" and taxonRank "cultivar group"); `Atlantis` (for scientificName "Paphiopedilum Atlantis grex" and taxonRank "grex").</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td><a href="http://rs.tdwg.org/abcd/terms/cultivarName">http://rs.tdwg.org/abcd/terms/cultivarName</a> or <a href="http://rs.tdwg.org/abcd/terms/cultivarGroupName">http://rs.tdwg.org/abcd/terms/cultivarGroupName</a> or <a href="http://rs.tdwg.org/abcd/terms/breed">http://rs.tdwg.org/abcd/terms/breed</a> (ABCD 3.0)</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwciri_footprintSRS"></a>Term Name  dwciri:footprintSRS</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/iri/footprintSRS">http://rs.tdwg.org/dwc/iri/footprintSRS</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/iri/version/footprintSRS-2021-06-25">http://rs.tdwg.org/dwc/iri/version/footprintSRS-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Footprint SRS (IRI)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The ellipsoid, geodetic datum, or spatial reference system (SRS) upon which the geometry given in footprintWKT is based.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Terms in the dwciri namespace are intended to be used in RDF with non-literal objects.</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_footprintSRS"></a>Term Name  dwc:footprintSRS</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/footprintSRS">http://rs.tdwg.org/dwc/terms/footprintSRS</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/footprintSRS-2021-06-25">http://rs.tdwg.org/dwc/terms/version/footprintSRS-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Footprint SRS</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The ellipsoid, geodetic datum, or spatial reference system (SRS) upon which the geometry given in footprintWKT is based.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Recommended best practice is to use the EPSG code of the SRS, if known. Otherwise use a controlled vocabulary for the name or code of the geodetic datum, if known. Otherwise use a controlled vocabulary for the name or code of the ellipsoid, if known. If none of these is known, use the value `unknown`. It is also permitted to provide the SRS in Well-Known-Text, especially if no EPSG code provides the necessary values for the attributes of the SRS. Do not use this term to describe the SRS of the decimalLatitude and decimalLongitude, nor of any verbatim coordinates - use the geodeticDatum and verbatimSRS instead.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`epsg:4326`, `GEOGCS["GCS_WGS_1984", DATUM["D_WGS_1984", SPHEROID["WGS_1984",6378137,298.257223563]], PRIMEM["Greenwich",0], UNIT["Degree",0.0174532925199433]]` (WKT for the standard WGS84 Spatial Reference System EPSG:4326)</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_genericName"></a>Term Name  dwc:genericName</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/genericName">http://rs.tdwg.org/dwc/terms/genericName</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/genericName-2021-06-25">http://rs.tdwg.org/dwc/terms/version/genericName-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Generic Name</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The genus part of the scientificName without authorship.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>For synonyms the accepted genus and the genus part of the name may be different. The term genericName should be used together with specificEpithet to form a binomial and with infraspecificEpithet to form a trinomial. The term genericName should only be used for combinations. Uninomials of generic rank do not have a genericName.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`Felis` (for scientificName "Felis concolor", with accompanying values of "Puma concolor" in acceptedNameUsage and "Puma" in genus).</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwciri_georeferenceVerificationStatus"></a>Term Name  dwciri:georeferenceVerificationStatus</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/iri/georeferenceVerificationStatus">http://rs.tdwg.org/dwc/iri/georeferenceVerificationStatus</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/iri/version/georeferenceVerificationStatus-2021-06-25">http://rs.tdwg.org/dwc/iri/version/georeferenceVerificationStatus-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Georeference Verification Status (IRI)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>A categorical description of the extent to which the georeference has been verified to represent the best possible spatial description for the Location of the Occurrence.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Recommended best practice is to use a controlled vocabulary. Terms in the dwciri namespace are intended to be used in RDF with non-literal objects.</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_georeferenceVerificationStatus"></a>Term Name  dwc:georeferenceVerificationStatus</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/georeferenceVerificationStatus">http://rs.tdwg.org/dwc/terms/georeferenceVerificationStatus</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/georeferenceVerificationStatus-2021-06-25">http://rs.tdwg.org/dwc/terms/version/georeferenceVerificationStatus-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Georeference Verification Status</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>A categorical description of the extent to which the georeference has been verified to represent the best possible spatial description for the Location of the Occurrence.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Recommended best practice is to use a controlled vocabulary.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`unable to georeference`, `requires georeference`, `requires verification`, `verified by data custodian`, `verified by contributor`</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>DataSets/DataSet/Units/Unit/Gathering/SiteCoordinateSets/SiteCoordinates/GeoreferenceVerificationStatus</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_identifiedByID"></a>Term Name  dwc:identifiedByID</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/identifiedByID">http://rs.tdwg.org/dwc/terms/identifiedByID</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/identifiedByID-2021-06-25">http://rs.tdwg.org/dwc/terms/version/identifiedByID-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Identified By ID</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>A list (concatenated and separated) of the globally unique identifier for the person, people, groups, or organizations responsible for assigning the Taxon to the subject.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Recommended best practice is to provide a single identifier that disambiguates the details of the identifying agent. If a list is used, the order of the identifiers on the list should not be assumed to convey any semantics. Recommended best practice is to separate the values in a list with space vertical bar space ( | ).</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`<a href="https://orcid.org/0000-0002-1825-0097`">https://orcid.org/0000-0002-1825-0097`</a> (for an individual), `<a href="https://orcid.org/0000-0002-1825-0097">https://orcid.org/0000-0002-1825-0097</a> | <a href="https://orcid.org/0000-0002-1825-0098`">https://orcid.org/0000-0002-1825-0098`</a> (for a list of people). </td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_individualCount"></a>Term Name  dwc:individualCount</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/individualCount">http://rs.tdwg.org/dwc/terms/individualCount</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/individualCount-2021-06-25">http://rs.tdwg.org/dwc/terms/version/individualCount-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Individual Count</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The number of individuals present at the time of the Occurrence.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`0`, `1`, `25`</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>DataSets/DataSet/Units/Unit/Gathering/SiteMeasurementsOrFacts/SiteMeasurementOrFact/MeasurementOrFactAtomised/LowerValue</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_infragenericEpithet"></a>Term Name  dwc:infragenericEpithet</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/infragenericEpithet">http://rs.tdwg.org/dwc/terms/infragenericEpithet</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/infragenericEpithet-2021-06-25">http://rs.tdwg.org/dwc/terms/version/infragenericEpithet-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Infrageneric Epithet</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The infrageneric part of a binomial name at ranks above species but below genus.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>The term infragenericEpithet should be used in conjunction with genericName, specificEpithet, infraspecificEpithet, taxonRank and scientificNameAuthorship to represent the individual elements of the complete scientificName. It can be used to indicate the subgenus placement of a species, which in zoology is often given in parentheses. Can also be used to share infrageneric names such as botanical sections (e.g., `Vicia sect. Cracca`).</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`Abacetillus` (for scientificName "Abacetus (Abacetillus) ambiguus", `Cracca` (for scientificName "Vicia sect. Cracca")</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>DataSets/DataSet/Units/Unit/Identifications/Identification/Result/TaxonIdentified/ScientificName/NameAtomised/Bacterial/Subgenus (for bacterial names) or  DataSets/DataSet/Units/Unit/Identifications/Identification/Result/TaxonIdentified/ScientificName/NameAtomised/Zoological/Subgenus (for zoological names) or DataSets/DataSet/Units/Unit/Identifications/Identification/Result/TaxonIdentified/ScientificName/NameAtomised/Botanical/FirstEpithet (for botanical names)</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_infraspecificEpithet"></a>Term Name  dwc:infraspecificEpithet</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/infraspecificEpithet">http://rs.tdwg.org/dwc/terms/infraspecificEpithet</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/infraspecificEpithet-2021-06-25">http://rs.tdwg.org/dwc/terms/version/infraspecificEpithet-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Infraspecific Epithet</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The name of the lowest or terminal infraspecific epithet of the scientificName, excluding any rank designation.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>In botany, where there can be more than one infraspecific rank, name strings may be provided, in literature and in identifications, that have more than two epithets. Only the last of these epithets is the infraspecificEpithet and only the first and the last epithets belong to the scientificName. For example: the infraspecificEpithet in the string "Indigofera charlieriana subsp. sessilis var. scaberrima" is `scaberrima` and the scientificName is `Indigophera charlieriana var. scaberrima`.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`concolor` (for scientificName "Puma concolor concolor"), `oxyadenia` (for scientificName "Quercus agrifolia var. oxyadenia"), `laxa` (for scientificName "Cheilanthes hirta f. laxa"), `scaberrima` (for scientificName "Indigofera charlieriana var. scaberrima").</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>DataSets/DataSet/Units/Unit/Identifications/Identification/TaxonIdentified/ScientificName/NameAtomised/Bacterial/SubspeciesEpithet or DataSets/DataSet/Units/Unit/Identifications/Identification/TaxonIdentified/ScientificName/NameAtomised/Botanical/SecondEpithet or DataSets/DataSet/Units/Unit/Identifications/Identification/TaxonIdentified/ScientificName/NameAtomised/Zoological/SubspeciesEpithet</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_lifeStage"></a>Term Name  dwc:lifeStage</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/lifeStage">http://rs.tdwg.org/dwc/terms/lifeStage</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/lifeStage-2021-06-25">http://rs.tdwg.org/dwc/terms/version/lifeStage-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Life Stage</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The age class or life stage of the Organism(s) at the time the Occurrence was recorded.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Recommended best practice is to use a controlled vocabulary.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`zygote`, `larva`, `juvenile`, `adult`, `seedling`, `flowering`, `fruiting`</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>DataSets/DataSet/Units/Unit/MycologicalUnit/MycologicalSexualStage or DataSets/DataSet/Units/Unit/MycologicalUnit/MycologicalLiveStages/MycologicalLiveStage or DataSets/DataSet/Units/Unit/ZoologicalUnit/PhasesOrStages/PhaseOrStage</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2019-12-01_19">http://rs.tdwg.org/decisions/decision-2019-12-01_19</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwciri_lifeStage"></a>Term Name  dwciri:lifeStage</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/iri/lifeStage">http://rs.tdwg.org/dwc/iri/lifeStage</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/iri/version/lifeStage-2021-06-25">http://rs.tdwg.org/dwc/iri/version/lifeStage-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Life Stage (IRI)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The age class or life stage of the Organism(s) at the time the Occurrence was recorded.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Recommended best practice is to use a controlled vocabulary. Terms in the dwciri namespace are intended to be used in RDF with non-literal objects.</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_locality"></a>Term Name  dwc:locality</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/locality">http://rs.tdwg.org/dwc/terms/locality</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/locality-2021-06-25">http://rs.tdwg.org/dwc/terms/version/locality-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Locality</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The specific description of the place.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Less specific geographic information can be provided in other geographic terms (higherGeography, continent, country, stateProvince, county, municipality, waterBody, island, islandGroup). This term may contain information modified from the original to correct perceived errors or standardize the description.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`Bariloche, 25 km NNE via Ruta Nacional 40 (=Ruta 237)`, `Queets Rainforest, Olympic National Park`</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>DataSets/DataSet/Units/Unit/Gathering/NamedAreas/NamedArea/AreaName</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_MaterialCitation"></a>Term Name  dwc:MaterialCitation</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/MaterialCitation">http://rs.tdwg.org/dwc/terms/MaterialCitation</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/MaterialCitation-2021-06-25">http://rs.tdwg.org/dwc/terms/version/MaterialCitation-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Material Citation</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>A reference to or citation of one, a part of, or multiple specimens in scholarly publications.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>This class constitutes a new value for the controlled vocabulary in the recommendations for basisOfRecord. When importing Darwin Core Archives of literature-based datasets to GBIF, the basisOfRecord should be changed from “Occurrence”, "PreservedSpecimen" or "Literature" to “MaterialCitation”.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>A citation of a physical specimen from a scientific collection in a taxonomic treatment in a scientific publication. A citation of a group of physical specimens, such as paratypes in a taxonomic treatment in a scientific publication. An occurrence mentioned in a field note book.</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Class</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwciri_measurementValue"></a>Term Name  dwciri:measurementValue</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/iri/measurementValue">http://rs.tdwg.org/dwc/iri/measurementValue</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/iri/version/measurementValue-2021-06-25">http://rs.tdwg.org/dwc/iri/version/measurementValue-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Measurement Value (IRI)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The value of the measurement, fact, characteristic, or assertion.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Terms in the dwciri namespace are intended to be used in RDF with non-literal objects.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`<a href="http://vocab.nerc.ac.uk/collection/L22/current/TOOL0960/`">http://vocab.nerc.ac.uk/collection/L22/current/TOOL0960/`</a></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_nameAccordingTo"></a>Term Name  dwc:nameAccordingTo</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/nameAccordingTo">http://rs.tdwg.org/dwc/terms/nameAccordingTo</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/nameAccordingTo-2021-06-25">http://rs.tdwg.org/dwc/terms/version/nameAccordingTo-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Name According To</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The reference to the source in which the specific taxon concept circumscription is defined or implied - traditionally signified by the Latin "sensu" or "sec." (from secundum, meaning "according to"). For taxa that result from identifications, a reference to the keys, monographs, experts and other sources should be given.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>This term provides context to the `scientificName`. Together with the `scientificName`, separated by ‘sensu’ or ‘sec.’, it forms the taxon concept label. When not provided explicitly within a Taxon Core data set, the `nameAccordingTo` can be taken to be the data set itself. In this case the data set mostly provides sufficient context to infer the delimitation of the taxon and its relationship with other taxa. When not provided explicitly within an Occurrence Core data set, `nameAccordingTo` can sometimes be an underlying taxonomy of the data set, such as Plants of the World Online (<a href="http://powo.science.kew.org/">http://powo.science.kew.org/</a>) for vascular plant records in iNaturalist, though in such cases `nameAccordingTo` should still be provided explicitly. In all other cases where there is no further context, the `nameAccordingTo` is basically determined by the `Identification` information within the Occurrence record.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`Franz NM, Cardona-Duque J (2013) Description of two new species and phylogenetic reassessment of Perelleschus Wibmer & O’Brien, 1986 (Coleoptera: Curculionidae), with a complete taxonomic concept history of Perelleschus sec. Franz & Cardona-Duque, 2013. Syst Biodivers. 11: 209–236.` (as the full citation of the Franz & Cardona-Duque (2013) in Perelleschus splendida sec. Franz & Cardona-Duque (2013)).</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2019-12-01_19">http://rs.tdwg.org/decisions/decision-2019-12-01_19</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_occurrenceStatus"></a>Term Name  dwc:occurrenceStatus</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/occurrenceStatus">http://rs.tdwg.org/dwc/terms/occurrenceStatus</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/occurrenceStatus-2021-06-25">http://rs.tdwg.org/dwc/terms/version/occurrenceStatus-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Occurrence Status</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>A statement about the presence or absence of a Taxon at a Location.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>For Occurrences, the default vocabulary is recommended to consist of "present" and "absent", but can be extended by implementers with good justification.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`present`, `absent`</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_organismQuantity"></a>Term Name  dwc:organismQuantity</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/organismQuantity">http://rs.tdwg.org/dwc/terms/organismQuantity</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/organismQuantity-2021-06-25">http://rs.tdwg.org/dwc/terms/version/organismQuantity-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Organism Quantity</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>A number or enumeration value for the quantity of organisms.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>An organismQuantity must have a corresponding organismQuantityType.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`27` (organismQuantity) with `individuals` (organismQuantityType). `12.5` (organismQuantity) with `% biomass` (organismQuantityType). `r` (organismQuantity) with `Braun Blanquet Scale` (organismQuantityType). `many` (organismQuantity) with `individuals` (organismQuantityType).</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2015-03-19_18">http://rs.tdwg.org/decisions/decision-2015-03-19_18</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_originalNameUsage"></a>Term Name  dwc:originalNameUsage</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/originalNameUsage">http://rs.tdwg.org/dwc/terms/originalNameUsage</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/originalNameUsage-2021-06-25">http://rs.tdwg.org/dwc/terms/version/originalNameUsage-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Original Name Usage</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The taxon name, with authorship and date information if known, as it originally appeared when first established under the rules of the associated nomenclaturalCode. The basionym (botany) or basonym (bacteriology) of the scientificName or the senior/earlier homonym for replaced names.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>The full scientific name, with authorship and date information if known, of the name usage in which the terminal element of the scientificName was originally established under the rules of the associated nomenclaturalCode. For example, for names governed by the ICNafp, this term would indicate the basionym of a record representing a subsequent combination. Unlike basionyms, however, this term can apply to scientific names at all ranks.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`Pinus abies`, `Gasterosteus saltatrix Linnaeus 1768`</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_originalNameUsageID"></a>Term Name  dwc:originalNameUsageID</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/originalNameUsageID">http://rs.tdwg.org/dwc/terms/originalNameUsageID</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/originalNameUsageID-2021-06-25">http://rs.tdwg.org/dwc/terms/version/originalNameUsageID-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Original Name Usage ID</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>An identifier for the name usage (documented meaning of the name according to a source) in which the terminal element of the scientificName was originally established under the rules of the associated nomenclaturalCode.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>This term should be used to refer to the taxonID of a Taxon record that represents the usage of the terminal element of the scientificName as originally established under the rules of the associated nomenclaturalCode. For example, for names governed by the ICNafp, this term would establish the relationship between a record representing a subsequent combination and the record for its corresponding basionym. Unlike basionyms, however, this term can apply to scientific names at all ranks. For Darwin Core Archives the related record should be present locally in the same archive.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`tsn:41107` (ITIS), `urn:lsid:ipni.org:names:320035-2` (IPNI), `2704179` (GBIF), `6W3C4` (COL)</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_parentNameUsageID"></a>Term Name  dwc:parentNameUsageID</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/parentNameUsageID">http://rs.tdwg.org/dwc/terms/parentNameUsageID</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/parentNameUsageID-2021-06-25">http://rs.tdwg.org/dwc/terms/version/parentNameUsageID-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Parent Name Usage ID</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>An identifier for the name usage (documented meaning of the name according to a source) of the direct, most proximate higher-rank parent taxon (in a classification) of the most specific element of the scientificName.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>This term should be used for accepted names to refer to the taxonID of a Taxon record that represents the next higher taxon rank in the same taxonomic classification. For Darwin Core Archives the related record should be present locally in the same archive.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`tsn:41074` (ITIS), `urn:lsid:ipni.org:names:30001404-2` (IPNI), `2704173` (GBIF), `6T8N` (COL)</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dcterms_references"></a>Term Name  dcterms:references</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://purl.org/dc/terms/references">http://purl.org/dc/terms/references</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://dublincore.org/usage/terms/history/#references-003">http://dublincore.org/usage/terms/history/#references-003</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>References</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>A related resource that is referenced, cited, or otherwise pointed to by the described resource.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>From Dublin Core, "This property is intended to be used with non-literal values. This property is an inverse property of Is Referenced By." The intended usage of this term in Darwin Core is to point to the definitive source representation of the resource (e.g.,Taxon, Occurrence, Event in Darwin Core), if one is available. Note that the intended usage of dcterms:bibliographicCitation in Darwin Core, by contrast, is to provide the preferred way to cite the resource itself.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>MaterialSample example: `<a href="http://arctos.database.museum/guid/MVZ:Mamm:165861`">http://arctos.database.museum/guid/MVZ:Mamm:165861`</a>, Taxon example: `<a href="https://www.catalogueoflife.org/data/taxon/32664`">https://www.catalogueoflife.org/data/taxon/32664`</a></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2011-10-16_7">http://rs.tdwg.org/decisions/decision-2011-10-16_7</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_relationshipOfResource"></a>Term Name  dwc:relationshipOfResource</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/relationshipOfResource">http://rs.tdwg.org/dwc/terms/relationshipOfResource</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/relationshipOfResource-2021-06-25">http://rs.tdwg.org/dwc/terms/version/relationshipOfResource-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Relationship Of Resource</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The relationship of the subject (identified by resourceID) to the object (identified by relatedResourceID).</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Recommended best practice is to use a controlled vocabulary.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`sameAs`, `duplicate of`, `mother of`, `offspring of`, `sibling of`, `parasite of`, `host of`, `valid synonym of`, `located within`, `pollinator of members of taxon`, `pollinated specific plant`, `pollinated by members of taxon`, ` on slab with`</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>DataSets/DataSet/Units/Unit/Associations/UnitAssociation/AssociationType</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_relationshipOfResourceID"></a>Term Name  dwc:relationshipOfResourceID</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/relationshipOfResourceID">http://rs.tdwg.org/dwc/terms/relationshipOfResourceID</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/relationshipOfResourceID-2021-06-25">http://rs.tdwg.org/dwc/terms/version/relationshipOfResourceID-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Relationship Of Resource ID</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>An identifier for the relationship type (predicate) that connects the subject identified by resourceID to its object identified by relatedResourceID.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Recommended best practice is to use the identifiers of the terms in a controlled vocabulary, such as the OBO Relation Ontology.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`<a href="http://purl.obolibrary.org/obo/RO_0002456`">http://purl.obolibrary.org/obo/RO_0002456`</a> (for the relation "pollinated by"), `<a href="http://purl.obolibrary.org/obo/RO_0002455`">http://purl.obolibrary.org/obo/RO_0002455`</a> (for the relation "pollinates"), `<a href="https://www.inaturalist.org/observation_fields/879`">https://www.inaturalist.org/observation_fields/879`</a> (for the relation "eaten by")</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwciri_samplingProtocol"></a>Term Name  dwciri:samplingProtocol</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/iri/samplingProtocol">http://rs.tdwg.org/dwc/iri/samplingProtocol</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/iri/version/samplingProtocol-2021-06-25">http://rs.tdwg.org/dwc/iri/version/samplingProtocol-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Sampling Protocol (IRI)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The methods or protocols used during an Event, denoted by an IRI.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Recommended best practice is describe an Event with no more than one sampling protocol. In the case of a summary Event in which a specific protocol can not be attributed to specific Occurrences, the recommended best practice is to repeat the property for each IRI that denotes a different sampling protocol that applies to the Occurrence.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`<a href="https://doi.org/10.1111/j.1466-8238.2009.00467.x`">https://doi.org/10.1111/j.1466-8238.2009.00467.x`</a></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_samplingProtocol"></a>Term Name  dwc:samplingProtocol</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/samplingProtocol">http://rs.tdwg.org/dwc/terms/samplingProtocol</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/samplingProtocol-2021-06-25">http://rs.tdwg.org/dwc/terms/version/samplingProtocol-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Sampling Protocol</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The names of, references to, or descriptions of the methods or protocols used during an Event.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Recommended best practice is describe an Event with no more than one sampling protocol. In the case of a summary Event with multiple protocols, in which a specific protocol can not be attributed to specific Occurrences, the recommended best practice is to separate the values in a list with space vertical bar space ( | ).</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`UV light trap`, `mist net`, `bottom trawl`, `ad hoc observation | point count`, `Penguins from space: faecal stains reveal the location of emperor penguin colonies, <a href="https://doi.org/10.1111/j.1466-8238.2009.00467.x`">https://doi.org/10.1111/j.1466-8238.2009.00467.x`</a>, `Takats et al. 2001. Guidelines for Nocturnal Owl Monitoring in North America. Beaverhill Bird Observatory and Bird Studies Canada, Edmonton, Alberta. 32 pp., <a href="http://www.bsc-eoc.org/download/Owl.pdf`">http://www.bsc-eoc.org/download/Owl.pdf`</a></td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>DataSets/DataSet/Units/Unit/Gathering/Method</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_scientificName"></a>Term Name  dwc:scientificName</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/scientificName">http://rs.tdwg.org/dwc/terms/scientificName</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/scientificName-2021-06-25">http://rs.tdwg.org/dwc/terms/version/scientificName-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Scientific Name</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The full scientific name, with authorship and date information if known. When forming part of an Identification, this should be the name in lowest level taxonomic rank that can be determined. This term should not contain identification qualifications, which should instead be supplied in the IdentificationQualifier term.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>This term should not contain identification qualifications, which should instead be supplied in the IdentificationQualifier term. When applied to an Organism or Occurrence, this term should be used to represent the scientific name that was applied to the associated Organism in accordance with the Taxon to which it was or is currently identified.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`Coleoptera` (order). `Vespertilionidae` (family). `Manis` (genus). `Ctenomys sociabilis` (genus + specificEpithet). `Ambystoma tigrinum diaboli` (genus + specificEpithet + infraspecificEpithet). `Roptrocerus typographi (Györfi, 1952)` (genus + specificEpithet + scientificNameAuthorship), `Quercus agrifolia var. oxyadenia (Torr.) J.T. Howell` (genus + specificEpithet + taxonRank + infraspecificEpithet + scientificNameAuthorship).</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>DataSets/DataSet/Units/Unit/Identifications/Identification/TaxonIdentified/ScientificName/FullScientificNameString</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
		<tr>
			<td>Executive Committee decision</td>
			<td><a href="http://rs.tdwg.org/decisions/decision-2019-12-01_19">http://rs.tdwg.org/decisions/decision-2019-12-01_19</a></td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_verbatimIdentification"></a>Term Name  dwc:verbatimIdentification</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/verbatimIdentification">http://rs.tdwg.org/dwc/terms/verbatimIdentification</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/verbatimIdentification-2021-06-25">http://rs.tdwg.org/dwc/terms/version/verbatimIdentification-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Verbatim Identification</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>A string representing the taxonomic identification as it appeared in the original record.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>This term is meant to allow the capture of an unaltered original identification/determination, including identification qualifiers, hybrid formulas, uncertainties, etc. This term is meant to be used in addition to `scientificName` (and `identificationQualifier` etc.), not instead of it.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`Peromyscus sp.`, `Ministrymon sp. nov. 1`, `Anser anser X Branta canadensis`, `Pachyporidae?`</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_verbatimLocality"></a>Term Name  dwc:verbatimLocality</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/verbatimLocality">http://rs.tdwg.org/dwc/terms/verbatimLocality</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/verbatimLocality-2021-06-25">http://rs.tdwg.org/dwc/terms/version/verbatimLocality-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Verbatim Locality</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The original textual description of the place.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`25 km NNE Bariloche por R. Nac. 237`</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>DataSets/DataSet/Units/Unit/Gathering/LocalityText</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwc_verticalDatum"></a>Term Name  dwc:verticalDatum</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/verticalDatum">http://rs.tdwg.org/dwc/terms/verticalDatum</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/terms/version/verticalDatum-2021-06-25">http://rs.tdwg.org/dwc/terms/version/verticalDatum-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Vertical Datum</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The vertical datum used as the reference upon which the values in the elevation terms are based.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Recommended best practice is to use a controlled vocabulary.</td>
		</tr>
		<tr>
			<td>Examples</td>
			<td>`EGM84`, `EGM96`, `EGM2008`, `PGM2000A`, `PGM2004`, `PGM2006`, `PGM2007`, `epsg:7030`, `unknown`</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>

<table>
	<thead>
		<tr>
			<th colspan="2"><a id="dwciri_verticalDatum"></a>Term Name  dwciri:verticalDatum</th>
		</tr>
	</thead>
	<tbody>
		<tr>
			<td>Term IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/iri/verticalDatum">http://rs.tdwg.org/dwc/iri/verticalDatum</a></td>
		</tr>
		<tr>
			<td>Modified</td>
			<td>2021-06-25</td>
		</tr>
		<tr>
			<td>Term version IRI</td>
			<td><a href="http://rs.tdwg.org/dwc/iri/version/verticalDatum-2021-06-25">http://rs.tdwg.org/dwc/iri/version/verticalDatum-2021-06-25</a></td>
		</tr>
		<tr>
			<td>Label</td>
			<td>Vertical Datum (IRI)</td>
		</tr>
		<tr>
			<td>Definition</td>
			<td>The vertical datum used as the reference upon which the values in the elevation terms are based.</td>
		</tr>
		<tr>
			<td>Notes</td>
			<td>Recommended best practice is to use a controlled vocabulary. Terms in the dwciri namespace are intended to be used in RDF with non-literal objects.</td>
		</tr>
		<tr>
			<td>ABCD equivalence</td>
			<td>not in ABCD</td>
		</tr>
		<tr>
			<td>Type</td>
			<td>Property</td>
		</tr>
	</tbody>
</table>



