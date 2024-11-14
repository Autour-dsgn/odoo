# __Variant - UX reportIntroduction__

This report is based on exercises provided by Odoo involving the customization of various Bootstrap card components.
However, due to limitations in the available information, such as:
- Context of use: Where and how the interface is used
- Interface objectives: The primary tasks users are expected to perform
- Usage data: User behaviors and interactions with the interface I am unable to provide a fully comprehensive report.


## Methodology

Typically, a five-step methodology is employed for more concrete projects. Here's a breakdown of these steps:

1. **Defining objectives and scope**
    - Objectives: Clearly define the evaluation goals: accessibility, usability, overall user experience, etc.
    - Scope: Delimit the specific features, pages, or screens to be analyzed.

2. **Data collection**
    - Heuristic analysis: Evaluate the interface based on established usability principles (Nielsen Norman Group; 10 rules developed by Jakob Nielsen).
    - User testing: Observe real users interacting with the product to identify pain points and challenges. **Also, note elements that work well to inform future development.
    - Quantitative data analysis: Examine usage metrics (bounce rate, time on page, etc.) and user feedback (surveys, comments).
    - Benchmarking: Compare the product with competitors or industry best practices.

3. **Identifying issues**
    - Issue prioritization: Prioritize issues based on their impact on user experience.
    - Issue documentation: Clearly describe each issue, including its context, frequency, and impact.

4. **Formulating recommendations**
    - Concrete solutions: Propose feasible solutions to address the identified issues.
    - Recommendation prioritization: Rank recommendations based on their priority and potential impact.

5. **Presenting results**
    - Clear and concise report: Present the audit results clearly and structured, using graphs and tables as needed (visuals are an integral part of effective communication in UX design).
    - Effective communication: Communicate the results to stakeholders in a way that highlights the importance of the recommendations.


## Audit Results

1. **Inconsistent color palette**
- *Analysis*:
The color palette used in some variants doesn't align with Odoo's brand guidelines, causing visual confusion.

- *Consequence*:
This inconsistency can negatively impact brand perception and overall user experience. Users may be disengaged or confused about how to proceed.

- *Recommendation*: Adopt a color palette consistent with Odoo's brand guidelines and ensure consistent color usage throughout the interface (hierarchy, structure, etc.).


2. **Insufficient Color Contrast**
- *Analysis*:
Certain color combinations used for text and card backgrounds have inadequate contrast, making reading difficult, especially for users with visual impairments. This also hinders the ability to differentiate between active and inactive elements, such as tabs.

- *Consequence*:
Reduced comprehension, eye strain, and a violation of WCAG 2.1 accessibility standards.

- *Recommendation*:
Increase contrast by using more distinct color combinations. Use a contrast checker tool like WebAIM Color Contrast Checker to ensure colors meet accessibility standards.


3. **Lack of Visual Cues for Navigation**
- *Analysis*:
Navigation primarily relies on color changes to indicate active or inactive states, which may be difficult for color-blind or visually impaired users to perceive. Additionally, clickable elements are not sufficiently highlighted.

- *Consequence*:
Users may struggle to navigate the interface and understand the current state of elements.

- *Recommendation*:
Use additional visual cues such as icons, borders, or font size changes to distinguish between active and inactive states. Maintain a logical reading order: horizontal, vertical, and transverse.


4. **Unclear Disabled Tabs**
- *Analysis*:
Disabled tabs do not provide sufficient information about their state or functionality.

- *Consequence*:
Users may become frustrated and confused about why certain tabs are disabled.

- *Recommendation*:
Use clear labels for disabled tabs, such as "Disabled" or "Unavailable." If necessary, provide additional information about the reason for the disabled state. Ideally, understand why this state is useful. Sometimes, it's better to hide it completely (using "visibility: hidden;" or "display: none;" with a conditional).


5. **Weak Active State for Second-Level Navigation**
- *Analysis*:
The active state of second-level navigation tabs is not sufficiently visible, making it difficult for users to identify the selected tab.

- *Consequence*:
Users may feel lost and confused, leading to errors.

- *Recommendation*:
Improve the visibility of the active state using more contrasting colors, borders, or drop shadows.


6. **Insufficient Loading Feedback**
- *Analysis*:
The loading indicators used do not provide enough visual feedback, which can frustrate users.

- *Consequence*:
Users may think the application is frozen or experiencing technical issues. This can lead to user abandonment.

- *Recommendation*:
Use more visually appealing loading indicators, such as progress bars or animations. Also, provide informative messages to indicate the loading status. However, this is becoming less common as interface loading times improve. Understand why this state is used and consider alternatives.
Note: These translations aim to maintain the technical accuracy and clarity of the original text while ensuring readability in English. For more specific contexts or nuances, consider consulting with a subject matter expert.


7. **Conclusion**
To summarize, the key recommendations to improve the user experience of Odoo's Bootstrap card variants are:
- Enhance visibility and contrast: Improve the clarity and distinctiveness of elements.
- Use clear visual cues for navigation: Employ clear visual indicators to guide users through the interface.
- Ensure a consistent color palette: Maintain a color scheme that aligns with the brand guidelines.
- Provide clear information about disabled elements: Clearly communicate the reasons behind disabled elements.
- Use effective loading indicators: Implement visually appealing and informative loading indicators.


8. **About the Variant B**
I found it frustrating to understand the purpose of the content. I attempted to incorporate Odoo's colors, emphasize the navigation, and highlight the three active tabs. While I kept the "Disabled" tab to adhere to the exercise, I personally believe it should be removed. I rearranged the two columns for a diagonal reading flow and tried to emphasize the sub-navigation while maintaining the two-column structure. However, I would have preferred a different system to better convey that there are three elements ("An item") to explore. The second tab, beyond simply aligning with Odoo's design, doesn't seem to serve a clear purpose. For the third tab, I tried to maintain visual consistency with the first tab, even though the presence of two date elements is quite disruptive.
