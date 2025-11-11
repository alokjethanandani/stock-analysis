Here’s a polished Markdown context engineering doc you can feed into Gemini Pro so it knows exactly how to process and summarize the customer 
# Customer Insights Summarization
**Purpose:** Provide Gemini Pro with all necessary context and instructions to summarize customer insights from a Google Doc containing research participant notes.

---

## Source Data Format
- **Location:** A single Google Doc containing multiple participant notes.
- **Structure:** Each participant's notes are stored in a **separate tab** (Google Doc section or page).
- **Content Type:** Qualitative and quantitative research notes from customer interviews or surveys.

---

## Research Scope
Gemini should extract, aggregate, and summarize insights across **all participants** in the study, producing counts, segments, and qualitative summaries as outlined below.

---

## Summarization Requirements

### 1. Customer Channel
- Identify whether each participant is from:
  - **Bill.com Direct Channel Customer**
  - **Accounting Firm**
- Provide total count in each category.

---

### 2. 1099 Filing Volume
- Count number of participants/customers in each segment:
  - **≤ 100 filings/year**
  - **> 100 filings/year**
- Provide counts and percentages for each bucket.

---

### 3. Participant Profiles
- Segment participants by **role** in their company (e.g., Owner, AP Manager, Accountant, Bookkeeper).
- Provide:
  - Count of participants in each role
  - Percent distribution by role

---

### 4. Existing BILL 1099 Filing Customer
- Segment participants into:
  - **Existing BILL customer**
  - **Prospective BILL customer**
- Provide count and percentage for each segment.

---

### 5. Competitor Solutions
- List all competitor solutions mentioned.
- For each, provide:
  - **Solution name**
  - **# of customers using it**

---

### 6. Key Customer Pain Points
- Summarize recurring pain points.
- Include frequency counts if mentioned by multiple participants.

---

### 7. Jobs to Be Done
Split into two subcategories:
- **Year-Round Jobs** – tasks performed throughout the year
- **Year-End Jobs** – tasks performed during filing season

---

### 8. Feedback on New 1099 Experience
Summarize feedback across the following sub-areas. Limit the number of bullets in each sub-area to 5 max.
1. **Prep 1099 Dashboard**
2. **Payment Categorization**
3. **Import Workflow**
4. **Forms Dashboard**
5. **E-Filing & Delivery Workflow**

---

### 9. Pricing Feedback
- Summarize qualitative and quantitative feedback about pricing.
- Note positive, negative, and neutral comments.

---

### 10. Unmet Needs & Workarounds
- List unmet customer needs.
- Describe any workarounds customers currently use.

---

### 11. Key Adoption Requirements
- Summarize what customers identify as must-haves before adopting the product.

---

### 12. Memorable Quotes
- Extract any quotes that are impactful, representative, or especially illustrative of customer sentiment.
- Show timestamp in video.
---

### 13. Feature Requests
- List all new feature requests.
- Describe the customer pain point and desired solution.
- List the partcipant's name and show timestamp in video.

---

### 14. Enhancement or Improvement Requests
- List all requests to improve existing features.
- Describe the customer pain point and desired solution.
- List the partcipant's name and show timestamp in video.

---

## Output Format
- **Sections**: Match the above numbered list exactly as headings.
- **Counts & Percentages**: Present quantitative findings in tables where possible.
- **Qualitative Insights**: Present as bullet points, grouped by theme.
- **Quotes**: Enclose in quotation marks, attribute by participant role (e.g., *AP Manager*).
- **Competitor List**: Present in a table with columns: Competitor Name | # Customers.

---

## Additional Instructions
- If a section is not discussed in the participant notes, explicitly state: *"No feedback provided."*
- Summaries should be concise but preserve important detail.
- Group similar feedback into themes to avoid duplication.
- Prioritize clarity and actionable insights for product and design teams.
