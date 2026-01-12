# e-lit-dataset
pit-stop 3

## Selection Criteria

### Primary Selection Criteria
1. **Formal Innovation**: Works that demonstrate innovative use of digital technologies for literary expression
2. **Platform Diversity**: Representation across different technical platforms (Twine, HTML5, JavaScript, Unity, etc.)
3. **Genre Variety**: Inclusion of multiple electronic literature genres (hypertext, generative literature, interactive fiction, visual poetry, etc.)
4. **Cultural Representation**: Works from diverse creators, languages, and cultural contexts

### Secondary Considerations
- Works featured in the Electronic Literature Collection (ELO)
- Works accessible through stable URLs (when possible)
- Works with clear metadata available

## Data Model: Column Justification

### Core Identification
- **id**: Unique identifier for database management and cross-referencing
- **title**: The work's title as it appears publicly
- **creator**: Attribution following the work's preferred naming conventions
- **year**: Creation/publication year for temporal contextualization

### Access and Technical Information
- **url**: Primary access point for experiencing the work
- **access_date**: When the URL was verified (important for link rot tracking)
- **type**: Genre classification based on digital literature taxonomies
- **technology**: Technical stack (crucial for preservation and emulation planning)
- **language**: Language(s) of the primary interface/narrative

### Analytical Categories
- **interaction_level**: Categorized as none/low/medium/high for comparative analysis
- **textuality**: Describes narrative structure (linear/non-linear/modular/database-like)
- **versioning**: Development status (stable/updated/multiple versions/unclear)
- **preservation_status**: Current accessibility (live/archived/partially broken/inaccessible)

### Source and Rights
- **metadata_source**: Primary documentation source (ELO in this case)
- **license**: Copyright/licensing information for fair use analysis
- **one_sentence_description**: Concise summary for quick reference

## Known Limitations and Biases

### Language Bias
- **Dominance of English**: While multilingual works are included, English remains the primary language of interface and documentation
- **Translation Gaps**: Non-English works often lack comprehensive metadata in other languages
- **Roman Script Preference**: Most works use Roman alphabet systems

### Platform and Technical Bias
- **Web-Centric Focus**: Most works are browser-based, underrepresenting native applications, installations, and physical computing works
- **"Survivorship Bias"**: Works preserved digitally are overrepresented compared to ephemeral or site-specific works
- **Accessibility Gaps**: Works requiring specific plugins, hardware, or proprietary software may be excluded or marked as inaccessible

### Temporal and Geographic Biases
- **21st Century Focus**: Most works post-date 2000, with fewer examples from earlier periods of electronic literature
- **Western Institutional Influence**: Strong representation from North American and European academic/artistic contexts
- **ELO-Centric**: Heavy reliance on Electronic Literature Organization's collections

### Discoverability Limitations
- **Institutional Affiliation**: Works from academic contexts are more discoverable than independent or community-based works
- **Publication Bias**: Works with scholarly documentation are overrepresented
- **Metadata Inconsistency**: Variable completeness of fields across entries
- **Link Rot**: Digital preservation challenges mean some URLs may become inactive after data collection

### Selection Methodology Constraints
- **Single Searcher**: Compiled by one researcher with particular interests and expertise
- **Time-Bound Collection**: Captures a snapshot of accessible works as of early 2026
- **Definitional Boundaries**: The category "electronic literature" itself carries historical and disciplinary assumptions
- **Missing Fields**: Some columns (like interaction_level, textuality) required inference rather than explicit documentation

## Remediation Strategies for Future Work

To address these limitations in future iterations:
1. **Multilingual Metadata Collection**: Partner with scholars across language communities
2. **Broader Platform Inclusion**: Actively seek non-web-based works
3. **Decolonial Approaches**: Prioritize works from underrepresented regions and creators
4. **Community Sourcing**: Develop participatory methods for work nomination and description
5. **Preservation Partnerships**: Collaborate with archives to document at-risk works
6. **Explicit Methodology**: Document selection decisions and gaps transparently

## Intended Uses

This dataset supports:
- Digital humanities pedagogy and curriculum development
- Comparative analysis of electronic literature forms
- Preservation tracking and risk assessment
- Platform and technology trend analysis
- Fair use and copyright education in digital contexts

## Acknowledgments

Primary metadata sourced from the Electronic Literature Organization's collections and public documentation. License information verified through direct source examination where possible. Descriptive summaries synthesized from creator statements and critical literature.
