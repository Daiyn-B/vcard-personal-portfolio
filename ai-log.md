You are assisting with a small, public static portfolio website.  
Project context:  
\- Purpose: present a student's skills and projects to internship reviewers.  
\- Existing system: an HTML/CSS/JavaScript portfolio template.  
\- Allowed changes: content, styling, and small front \- end corrections only.  
\- Do not add: a backend, login system, analytics tracker, or external data  
collection.  
Acceptance criteria:  
1\. The landing page displays my name and a concise professional role.  
2\. The portfolio contains at least two projects with a title and description.  
3\. The navigation links move to the correct sections.  
4\. The page is readable on a narrow mobile viewport.  
5\. No placeholder name, email address, or image remains in the published site.  
Constraints:  
\- Do not invent education, work history, awards, links, or technical skills.  
\- Preserve required license and attribution.  
\- Keep the site usable on mobile screens.  
\- Maintain readable contrast, keyboard navigation, meaningful link text,  
and useful image alternative text.  
\- Do not expose private information.  
First provide:  
1\. A file \- by \- file implementation plan.  
2\. Any Assumptions or risks.  
3\. A proposed test checklist.  
4\. Any questions that must be answered before implementation.  
Do not modify files until the plan is reviewed

Prompt Response:   
\#\#\# 1\. File-by-File Implementation Plan

\* \*\*\`index.html\`\*\*  
\* Update the landing section (\`\<header\>\` / \`\#hero\`) with your name and concise professional role.  
\* Replace placeholder project entries with at least two explicit project cards containing actual titles and concise descriptions.  
\* Verify and correct anchor target IDs (\`href="\#about"\`, \`href="\#projects"\`, \`href="\#contact"\`) to ensure navigation links work smoothly.  
\* Scrub all placeholder text (e.g., "John Doe", "user@example.com", lorem ipsum), placeholder images, and generic links.  
\* Add or update meaningful \`alt\` text for all images and descriptive anchor text for links.  
\* Verify license and original template attribution notices in footer or source comments remain intact.

\* \*\*\`styles.css\` / \`style.css\*\*\`  
\* Adjust typography and layout properties (flexbox/grid) to guarantee responsive behavior down to a 320px mobile viewport.  
\* Ensure color contrast ratios meet WCAG AA guidelines for body text and interactive elements.  
\* Add or maintain clear \`:focus\` / \`:focus-visible\` outline styles for keyboard navigation on links and buttons.

\* \*\*\`script.js\` / \`main.js\*\*\` (if present)  
\* Maintain light dynamic behaviors (e.g., mobile navigation toggle, smooth scrolling).  
\* Scrub any external analytics code, dynamic tracking scripts, or backend form submit hooks.  
\* Ensure non-critical JavaScript fails gracefully so static HTML content remains fully visible.

\---

\#\#\# 2\. Assumptions & Risks

\* \*\*Assumptions:\*\*  
\* You will provide your specific name, professional title, and project details to replace the placeholders.  
\* Existing open-source template licenses (e.g., MIT, CC-BY) allow modification while retaining the attribution text.  
\* No dynamic contact form backend is required; contact info will be provided strictly via mailto or plain text links.

\* \*\*Risks:\*\*  
\* \*\*Incomplete Content:\*\* If actual project descriptions or professional titles are missing, placeholder content might inadvertently remain.  
\* \*\*Layout Overflow:\*\* Large fixed-width visual elements or long code snippet text in project cards could break mobile viewport margins.

\---

\#\#\# 3\. Proposed Test Checklist

\* \[ \] \*\*Acceptance Criteria Verification\*\*  
\* \[ \] Landing page displays your explicit name and concise role.  
\* \[ \] Portfolio features at least 2 complete project cards (title \+ description).  
\* \[ \] Header/nav links scroll to the correct section IDs without broken targets.  
\* \[ \] Zero placeholder data remains (names, emails, lorem ipsum, \`src="holder.js"\`).

\* \[ \] \*\*Accessibility & Usability\*\*  
\* \[ \] All interactive elements are reachable and operable via the \`Tab\` key.  
\* \[ \] Text contrast meets minimum readable limits across dark/light elements.  
\* \[ \] All images contain descriptive \`alt\` attributes (or \`alt=""\` if purely decorative).

\* \[ \] \*\*Mobile Responsiveness\*\*  
\* \[ \] Page renders cleanly at 320px–375px wide viewports without horizontal scrolling.  
\* \[ \] Mobile navigation toggles open/close properly or collapses cleanly.

\* \[ \] \*\*Constraint Compliance\*\*  
\* \[ \] No external tracking scripts, login features, or backend endpoints included.  
\* \[ \] Template attribution/license notice is present and untouched.

\---

\#\#\# 4\. Questions Before Implementation

To finalize the content without inventing any information:

1\. What \*\*Name\*\* and \*\*Professional Role/Title\*\* should be displayed on the landing page?  
2\. What are the \*\*Titles\*\* and \*\*Descriptions\*\* for the two (or more) projects you would like included?  
3\. Which contact methods (e.g., GitHub profile URL, LinkedIn URL, public email) should be listed?  
