{
  "metadata": {
    "title": "I can format your assessment in Markdown",
    "unitId": 0,
    "unitName": "",
    "yearLevel": "",
    "subject": "",
    "totalMarks": 100,
    "estimatedDuration": "",
    "instructions": "Please paste the assessment (or the structured_assessment JSON) and tell me whether you want a Student version (no answers), an Answer Key, or both.",
    "createdAt": ""
  },
  "questions": [
    {
      "id": "template",
      "type": "short-answer",
      "marks": 1,
      "question": "Paste your assessment details and I will return a neatly formatted Markdown version. If you provide the JSON, I’ll auto-convert it.",
      "answers": [
        {
          "id": "what-i-need",
          "content": "Send either: 1) structured_assessment JSON; or 2) plain text with title, metadata, instructions, and questions. Also specify Student vs Answer Key.",
          "isCorrect": true,
          "explanation": "Below is the Markdown template I will use."
        }
      ],
      "rubric": "Markdown output template:\n\n# Assessment Title\n\n- Unit: <Unit Name> (ID: <Unit ID>)\n- Year Level: <Year Level>\n- Subject: <Subject>\n- Total Marks: <Total Marks>\n- Estimated Duration: <Estimated Duration>\n- Created: <Created At>\n\nInstructions:\n> <Instructions>\n\n## Questions\n\n1) [<Marks> marks] <Question text>\n   - A) <Option A>\n   - B) <Option B>\n   - C) <Option C>\n   - D) <Option D>\n   Answer (for Answer Key version): <Correct option and brief explanation>\n\n2) [<Marks> marks] <Short-answer question>\n   Answer (for Answer Key version): <Model answer>\n   Rubric: <If provided>\n\n— Repeat for all questions —"
    }
  ]
}