# ISBN-Range-Message
The RangeMessage.xml file from the ISBN International Agency

The authoritative file is downloadable from the agency website, currently from [this](https://www.isbn-international.org/range_file_generation) page.

## File contents and use

The XML file defines the canonical valid ranges for ISBNs.

Aside from structural issues, such as the validity of the checksum, the length of the ISBN, and the presence of invalid characters, an ISBN can still be unacceptable for a number of reasons:

* It might not start with either of the two currently valid EAN values of 978 and 979
* The EAN might not be followed by a valid registrant code.
* The registrant element might not be within a range issued by the agency.

## ISBN structure

An ISBN is constructed from five components.

* The EAN.UCC prefix: currently only 978 and 979 are valid.
* The registration group element: identifies the country, geographical region, or language
area. Length of this element is between one and five digits.
* The registrant element: identifies a publisher or imprint
The latest known version is Thu, 3 Aug 2017 16:45:46 CEST

The ISBN agency does not provide a notification mechanism for updates
