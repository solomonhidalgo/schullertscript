# German Lecture Translation Project

## Task
Translate German lecture transcripts to English .srt subtitle files.

## Source Files
- German transcripts are .txt files with format: `MM:SS German text`
- Currently working on: 04_Tangentialra_ume_2014_04_24.txt

## Workflow
1. Read the German .txt transcript
2. Translate ~100-150 entries at a time (as a language task, not dictionary lookup)
3. Append translated entries to the corresponding .srt file
4. After each batch, commit progress with message like "Translated entries 1-150"
5. Continue until complete

## Rules
- PRESERVE ALL TIMING EXACTLY
- Use proper .srt format (sequential numbering, HH:MM:SS,mmm --> HH:MM:SS,mmm)
- Topic is differential geometry/mechanics - use correct math terminology (manifold, tangent space, etc.)

## Progress Tracking
Check the .srt file to see how many entries are done, then continue from there.
