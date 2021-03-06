#######
History
#######

Putting the U into USFM
=======================

The arrival of affordable microcomputers encouraged many people to develop technology for Bible translation. Standard
Formatting Markup (SFM) emerged as a popular format among Bible translators. The basic, backslash-based syntax was used
in many different ways, within United Bible Societies (UBS) and beyond.

In 2002 UBS created a working group to produce a clear specification for one SFM dialect that would facilitate the sharing
of Scripture content between teams, organizations and technologies. That specification became Unified Standard Formatting Markup
(USFM).

https://paratext.org/usfm/

The Paratext Ecosystem
======================

In parallel with the rise of USFM, the Paratext Scripture translation tool has gradually become the reference software
for Bible translation. Paratext itself is a desktop application, but it is now part of an ecosystem that includes the Paratext
registry, as well as an archiving server for project, which enables translation teams to collaborate and to track progress. Various
technologies take advantage of this ecosystem, eg Publishing Assistant and Glisten.

https://registry.paratext.org

http://pubassist.paratext.org/

Every Tribe Every Nation and the Digital Bible Library
======================================================

Every Tribe Every Nation (ETEN) is a global initiative to bring together major stakeholders in Bible translation, with the goal of creating
translations of Scripture in every spoken language in the world by 2033. The Digital Bible Library is one key component of the ETEN, providing
an archiving and licensing platform for Scripture. DBL is oriented toward publication, in contrast to the Paratext translation ecosystem. Text
translations are stored as USX (the XML expression of USFM) and metadata is stored as an XML document. DBL is now part of the publishing toolchain
of many organizations including YouVersion and Biblesearch.

https://eten.org/

https://thedigitalbiblelibrary.org/about/

New Media, New Ecosystems
=========================

Initially, DBL stored text entries derived from Paratext projects. Audio recordings were soon added, with their own metadata XML schema. DBL also
stores print-oriented entries, typically produced by Publishing Assistant, as well as braille and sign language video entries. Rather than produce
and maintain a growing number of schema, it was decided to adopt a generic metadata model that could be extended to incorporate new types of entry.
That generic schema is DBL Metadata 2.0, which was rapidly patched to 2.1 and then 2.2.

While Paratext will continue to upload much of the text content of DBL, uploading of other entry types is now handled by Nathanael, an
application developed by the DBL team. Bible text editors such as Autographa are being developed to meet the needs of teams with modest language
and technology skills. Groups such as Unfolding Word, Wycliffe Associates and Faith Comes By Hearing are developing ecosystems for users of their
own systems. This is the context within which the ETEN Bible Tools committee identified a need for data exchange formats, leading to Scripture Burrito.

https://www.unfoldingword.org/tcore-project

https://www.faithcomesbyhearing.com/audio-bibles/render

https://www.autographa.com/

Building on DBL Metadata
========================

The ETEN Bible Tools Portability Subcommittee looked at various options and decided to base its work on the "DBL Bundle", which consists of DBL metadata
XML plus resources such as USX or MP3 files. This format has already been shown to work for thousands of entries. The subcommittee also identified areas
which required significant work. The DBL origins of the first Scripture Burrito specification are therefore clear, but there are multiple breaking changes.