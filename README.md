
App link:https://structuraldefects-j8ctohcvirwcduuvbyxk24.streamlit.app/

An AI-powered structural defect detection engine built using  Google Gemini for multimodal understanding. The
solution includes:
1. Image Upload & Preprocessing:
o Site engineers upload construction site images via a front-end interface
(Streamlit).
o Images are preprocessed for size normalization and noise reduction.
2. AI-Powered Defect Detection:
o The model analyzes the images to identify construction defects such as:
 Concrete cracks
 Honeycombing
 Plaster inconsistencies
 Surface irregularities
o Google Gemini API is integrated for high-fidelity visual and contextual
understanding.

3. Structured Output Generation:
o Results are returned in a structured tabular format with:
 Defect type
 Location (Zone/Floor)
 Severity (Low/Medium/High)
 Suggested corrective actions

4. Downloadable Reports:
o Output can be exported into Word/PDF format for compliance and audit
purposes.
