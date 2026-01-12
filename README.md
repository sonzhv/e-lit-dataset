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
- **year**: Publication year

### Access and Technical Information
- **url**: Primary access point for experiencing the work
- **access_date**: When the URL was verified
- **type**: Genre classification
- **technology**: Technical stack
- **language**: Language(s) of the primary interface/narrative

### Analytical Categories
- **interaction_level**: Categorized as none/low/medium/high for comparative analysis
- **textuality**: Describes narrative structure (linear/non-linear/modular/database-like)
- **versioning**: Development status (stable/updated/multiple versions/unclear)
- **preservation_status**: Current accessibility (live/archived/partially broken/inaccessible)

### Source and Rights
- **metadata_source**: Primary documentation source (I chose ELO)
- **license**: Copyright/licensing information
- **one_sentence_description**: Concise summary for quick reference

## Known Limitations and Biases

### Language Bias
- **Dominance of English**: While multilingual works are included, English remains the primary language of interface and documentation
- **Translation Gaps**: Non-English works often lack comprehensive metadata in other languages
- **Roman Script Preference**: Works use Roman alphabet systems

### Platform and Technical Bias
- **Web-Centric Focus**: Works are browser-based, underrepresenting native applications, installations, and physical computing works
- **Accessibility Gaps**: I didn't include works requiring specific plugins, hardware, or proprietary software

### Temporal and Geographic Biases
- **21st Century Focus**: Works post-date 2000
- **Western Institutional Influence**: Strong representation from North American and European academic/artistic contexts

### Discoverability Limitations
- **Institutional Affiliation**: Works from academic contexts are more discoverable than independent or community-based works
- **Publication Bias**: Works with scholarly documentation are overrepresented
- **Link Rot**: Digital preservation challenges mean some URLs may become inactive after data collection

### Selection Methodology Constraints
- **Single Searcher**: Compiled by one researcher with particular interests and expertise
- **Missing Fields**: Some columns (like interaction_level, textuality) required inference rather than explicit documentation

## Data Dictionary Note

No separate data dictionary file was created because:
1. All column meanings and controlled values are explained in the "Data Model" section above
2. No formal controlled vocabulary was established beyond the categorical values described
3. Most values (interaction_level, textuality, etc.) were inferred from work analysis rather than pre-defined

Key categorical values used:
- **interaction_level**: none / low / medium / high (based on user input required)
- **textuality**: linear / non-linear / modular / database-like (based on narrative structure)
- **preservation_status**: live / archived / partially broken / inaccessible (based on URL testing)
- **versioning**: stable / updated / multiple versions / unclear (based on development activity)

These categories were developed iteratively during analysis rather than as a pre-defined schema.
