# Overall Validation Summary

| Metric | Score (%) |
|---------|-----------|
| Overall Validation Score | 0 |
| Accuracy Score | 0 |
| Efficiency Score | 0 |
| Completeness Score | 0 |
| Overall Status | FAIL |

---

# Completeness Assessment

| Severity | Area | Issue | Recommendation |
|----------|------|-------|-----------------|
| High | Input Validation | OSI Semantic Model YAML file is missing from the input zip. Only Data Glossary PDF was provided. | Ensure both required artifacts (OSI Semantic Model YAML and Data Glossary) are included in the input zip file. |
| High | Object Coverage | Cannot validate dataset-to-table mapping without the semantic model. | Provide the OSI Semantic Model YAML file to enable completeness validation. |
| High | Relationship Coverage | Cannot validate relationships without the semantic model. | Provide the OSI Semantic Model YAML file to enable relationship validation. |
| High | Mapping Coverage | Cannot validate metric/measure definitions without the semantic model. | Provide the OSI Semantic Model YAML file to enable mapping validation. |

---

# Accuracy Assessment

| Severity | Area | Issue | Recommendation |
|----------|------|-------|-----------------|
| High | Input Validation | OSI Semantic Model YAML file is missing, blocking all accuracy validation checks. | Provide the OSI Semantic Model YAML file to enable accuracy validation. |
| High | Metadata/Technical Accuracy | Cannot validate type consistency without semantic model context. | Provide the OSI Semantic Model YAML file to enable type accuracy validation. |
| High | Business Definition Accuracy | Cannot validate business definition alignment without semantic model. | Provide the OSI Semantic Model YAML file to enable business definition validation. |

---

# Efficiency Assessment

| Severity | Area | Issue | Recommendation |
|----------|------|-------|-----------------|
| High | Input Validation | OSI Semantic Model YAML file is missing, blocking all efficiency validation checks. | Provide the OSI Semantic Model YAML file to enable efficiency validation. |
| High | Redundant Metadata | Cannot detect redundant definitions without semantic model. | Provide the OSI Semantic Model YAML file to enable redundancy detection. |
| High | Duplicate Documentation | Cannot detect duplicate metrics without semantic model. | Provide the OSI Semantic Model YAML file to enable duplicate detection. |
