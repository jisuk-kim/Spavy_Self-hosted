<%*
let title = await tp.system.prompt("Note Title 입력 (회사명_회의목적):");
let date = await tp.system.prompt("Enter the date (e.g., YYYY-MM-DD):", tp.date.now("YYYY-MM-DD"));
let tags = await tp.system.prompt("Enter tags (comma-separated):");
let party1Attendees = await tp.system.prompt("삼인 참석자 (comma-separated):");
let party2Attendees = await tp.system.prompt("상대방 참석자 (comma-separated):");
let agenda = await tp.system.prompt("Agenda 입력 (comma-separated):");
await tp.file.rename(`${title} - ${date}`);
tR += `---
tags: [${tags}]
created: ${date}
---
# ${title} - ${date}

## Attendees
| Party   | Attendees                          |
|---------|------------------------------------|
| 삼인 참석자 | ${party1Attendees.split(',').join(', ')} |
| 상대 참석자 | ${party2Attendees.split(',').join(', ')} |

(Add more parties as needed)

## Agenda
${agenda.split(',').map(item => `- ${item.trim()}`).join('\n')}

## Details of Discussion
-

## Results
-

## Action Items
- [ ] 
- [ ] 

## Link
- [Link Title](URL)

## Other Comments
- 
`;
%>