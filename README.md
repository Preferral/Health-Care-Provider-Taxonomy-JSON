Health Care Provider Taxonomy JSON
==================================

Version 14.0 January 2014

## Contents

> #### Individual or Groups (of Individuals)
>> * Group
>> * Allopathic & Osteopathic Physicians
>> * Behavioral Health & Social Service Providers
>> * Chiropractic Providers
>> * Dental Providers
>> * Dietary & Nutritional Service Providers
>> * Emergency Medical Service Providers
>> * Eye and Vision Services Providers
>> * Nursing Service Providers
>> * Nursing Service Related Providers
>> * Other Service Providers
>> * Pharmacy Service Providers
>> * Physician Assistants & Advanced Practice Nursing Providers
>> * Podiatric Medicine & Surgery Service Providers
>> * Respiratory, Developmental, Rehabilitative and Restorative Service Providers
>> * Speech, Language and Hearing Service Providers
>> * Student, Health Care
>> * Technologists, Technicians & Other Technical Service Providers
>
> #### Non-individual
>> * Agencies
>> * Ambulatory Health Care Facilities
>> * Hospital Units
>> * Hospitals
>> * Laboratories
>> * Managed Care Organizations
>> * Nursing & Custodial Care Facilities
>> * Other Service Providers
>> * Residential Treatment Facilities
>> * Respite Care Facility
>> * Suppliers
>> * Transportation Services
￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼￼

## Introduction

The Health Care Provider Taxonomy code set is an external, nonmedical data code set designed for use in an electronic environment, specifically within the ASC X12N Health Care transactions. This includes the transactions mandated under HIPAA.

The taxonomy code is a unique alphanumeric code, ten characters in length. The code set is structured into three distinct "Levels" including Provider Type, Classification, and Area of Specialization.

> #### Level I, Provider Type
> A major grouping of service(s) or occupation(s) of health care providers. For example: Allopathic & Osteopathic Physicians, Dental Providers, Hospitals, etc.
>
> #### Level II, Classification
> A more specific service or occupation related to the Provider Type. For example, the Classification for Allopathic & Osteopathic Physicians is based upon the General Specialty Certificates as issued by the appropriate national boards. The following boards will however, have their general certificates appear as Level III areas of specialization strictly due to display limitations of the code set for Boards that have multiple general certificates: Medical Genetics, Preventive Medicine, Psychiatry & Neurology, Radiology, Surgery, Otolaryngology, Pathology.
>
> #### Level III, Area of Specialization
> A more specialized area of the Classification in which a provider chooses to practice or make services available. For example, the Area of Specialization for provider type Allopathic & Osteopathic Physicians is based upon the Subspecialty Certificates as issued by the appropriate national boards.

The code set Levels are organized to allow for drilling down to the provider's most specific level of specialization. The ten digit codes for each provider category are unique and contain no embedded logic. The codes and categories are to be used exactly as they are assigned in the taxonomy list. At no time should codes be separated to form new codes, parsed apart, or edited on any one position within the code.

The taxonomy codes are self-selected by the provider. The taxonomy codes are organized based on education and training and are used to define specialty, not specific services that are rendered. Selection of a taxonomy code does not replace any credentialing or validation process that the organization requesting the code should complete. Definitions for some of the codes reference specialty or certifying boards as a source, but this reference in no way implies that providers have met the requirements of that board if they choose the code to identify themselves.

The code set is published (released) twice a year in January and July. The January publication is effective for use on April 1st and the July publication is effective for use on October 1st. The time between the publication release and the effective date is considered an implementation period to allow providers, payers, and vendors an opportunity to incorporate any changes into their systems.

### Historical Background

In the absence of an all-encompassing Provider Classification System, both ASC X12N and the National Provider System Workgroup from the Centers for Medicare & Medicaid Services (CMS) began work on identifying and coding an external provider code set that would be able to codify provider type and provider area of specialization for all health care related providers. CMS' intent was to provide a single coding structure to support work on the National Provider System, while X12N needed a single common code set for trading partner use. The two projects worked independently to some extent until April 1996 when the lists were coordinated and a single taxonomy code set was proposed. A sub-group of X12N TG2 WG15 (Provider Information Work Group) was charged with resolving differences in the two proposed taxonomy code sets. Their work resulted in a single taxonomy code set that both CMS and members of X12N found meaningful, easy to use, and functional for electronic transactions.

The sub-group initially started with the CMS draft taxonomy code set. This list incorporated all types of providers associated with health care in various ways, e.g. technologists or technicians who support or repair equipment/machinery, contractors, physicians, dentists, suppliers. A number of the providers offer health services, in concert with others, and do not or cannot bill independently for their services. The amount of research to validate and classify all providers using the proposed hierarchical structure was enormous. The X12N sub-group focused on health care providers who are licensed practitioners, those who bill for health-related services rendered, and those who appeared on the Medicare CMS Provider Specialty listing. This included providers who were licensed to practice medicine via state licensure agencies. In addition, a very broad definition of "areas of specialization" was used, which included nationally recognized specialties, provider self-designated specialties, areas of practice focus, and any request by any agency or trading partner submitted before the first taxonomy release. This level of detail captured specialty information in categories detailed enough to support those trading credentialing information, yet broad enough to support those wishing to trade directory level specialization information.

In 2001, X12N asked the National Uniform Claim Committee (NUCC) to become the official maintainer of the Health Care Provider Taxonomy code set. The NUCC has a formal operating protocol, including the Code Set Subcommittee’s processes. The NUCC is a diverse group of health care industry stakeholders representing providers, payers, designated standards maintenance organizations, public health organizations, and vendors.