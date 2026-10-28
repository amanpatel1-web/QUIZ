# Quiz PDF organization and chapter mapping

## Structure
Files are organized as `Class → Subject → NCERT chapter (or Review Needed bucket) → Exam → PDF`.

The PDFs are the existing NEET question sets. Their original filenames and file contents are preserved. This change moves the files in the repository; it does not change the deployed website code.

## Mapping confidence
This mapping was initially created from filenames. The user has confirmed that the PDF contents and answer keys are correct; no further content/answer-key verification is required. That confirmation does not by itself confirm every file's exact NCERT chapter placement or current exam-syllabus applicability. Rows marked “Review Needed”, “provisional”, or “partial-topic” remain flagged only for chapter mapping, topic scope, or syllabus alignment.

## Inventory
- Biology: 32 PDFs
- Chemistry: 21 PDFs
- Physics: 25 PDFs
- Total: 78 NEET PDFs
- JEE Main, JEE Advanced and CBSE Board PDFs: none identified in the current Quiz inventory.
- Mathematics: no PDF inventory currently present; Mathematics is not a NEET subject, but separate JEE/CBSE Math sets would be needed for those exams.

## Review-needed items
- **Chemistry:** Chemical Equilibrium and Ionic Equilibrium are mapped to Class 11 *Equilibrium* as separate partial-topic PDFs; inspect their contents. “Organic Compounds Containing Nitrogen” is provisionally associated with Class 12 *Amines*, but its title is broader. “Nuclear Chemistry” and “p-Block Elements” have been placed under Class Unconfirmed pending confirmation against the current NCERT/target-exam syllabus.
- **Physics:** “Center of Mass and Collision”, “Electrostatics”, “Heat and Thermodynamics”, “Properties of Matter”, and “Vector Algebra” are in Review Needed buckets because the filenames may cover multiple chapters or a topic rather than one exact NCERT chapter.
- **Potential filename-based coverage gaps:** no clearly titled PDF was found for Class 12 Physics *Atoms* or *Nuclei*, Class 12 Chemistry *Aldehydes, Ketones and Carboxylic Acids*, or Class 11 Physics *Kinetic Theory*. Some content could be present inside another PDF; the filename-based inventory alone cannot establish that. Mechanical-properties chapters may be included in “Properties of Matter”, and the Class 11 thermal/thermodynamics chapters may be combined in “Heat and Thermodynamics”.
- Biology has a filename-level match for each of the 19 Class 11 and 13 Class 12 chapters in the current starter syllabus list. The user has confirmed the PDF contents and answer keys; chapter-to-syllabus alignment remains a separate mapping question.

## Exam scope warning
The presence of a PDF in the NEET folder means only that its filename identifies it as a NEET question set. It does not independently certify that every question is in the current NEET syllabus. Confirm exam-year syllabus applicability separately for NEET, JEE Main, JEE Advanced and CBSE Board.

## Full file-by-file mapping
See `CHAPTER-PDF-MAPPING.csv` for original path, target class, subject, chapter/review bucket, exam, mapping status and new path.
