# Custom Instructions: Creating Git/Fabric Labs

When creating lab content in this repository, follow these conventions:

## Structure
- Each lab should be in its own folder: `labs/lab##/` where ## is a zero-padded number
- Main content in `lab##.md` file
- Images in an `images/` subfolder within each lab folder
- Use clear, descriptive titles with format: "# Lab ## - [Action] [Topic]"

## Writing Style
- Use imperative mood for steps ("Click", "Select", "Configure")
- Number all steps sequentially
- Include clear prerequisites or context before steps begin
- End with Questions and Next Steps sections

## Formatting Conventions
- Use **bold** for UI elements, button names, and important terms
- Use `code formatting` for file names, paths, and technical values
- Use keyboard shortcuts format: <kbd>Ctrl</kbd>
- Include screenshots with descriptive alt text and reference them with relative paths
- Use Markdown alerts for special information:
  - `> [!TIP]` for helpful hints
  - `> [!NOTE]` for informational callouts
  - `> [!IMPORTANT]` for critical information
  - `> [!CAUTION]` for warnings

## Content Organization
- **Steps section**: Numbered, detailed instructions with screenshots
- **Exercise sections**: Hands-on tasks for learners (numbered like Exercise 2.1)
- **Questions section**: Thought-provoking questions to reinforce learning
- **Next Steps section**: Navigation links to next lab and home

## Navigation
- Always include links to next lab using relative paths: `/labs/lab##/lab##.md`
- Always include link back to home: `README.md`
- Format: `- [Lab Title](/labs/lab##/lab##.md)`

## Technical Details
- Assume Microsoft Fabric/Power BI context
- Include workspace and resource naming conventions (e.g., adding initials)
- Reference official Microsoft Learn documentation when appropriate
- Explain why certain configurations are needed

## Images
- Store all images in lab-specific `images/` folder
- Use descriptive filenames with hyphens: `create-new-workspace.png`
- Reference with relative paths: `images/filename.png`