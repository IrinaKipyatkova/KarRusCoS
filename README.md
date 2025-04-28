# KarRusCoS
The corpus includes audio recordings of Livvi-Karelian speech with code-switching (Karelian-Russian) as well as annotations including the speaker’s identification number, gender, transcripts of utterances, the duration of each phrase, the number of words in Karelian, the number of words in Russian, the number of words with intra-word code-switching, the total number of words in a phrase and the recording’s quality mark. The corpus contains samples from 42 speakers. The total audio duration is 3.5 hours. The duration of recordings with good quality is about 3 hours. The KarRusCoS DB is intended for training and testing systems for automatic recognition of Karelian speech.

Each phrase is contained in a separate WAV file in mono with 16 kHz sampling rate and 16-bit audio quality. Annotations are represented in JSON format. A separate JSON file was created for each speaker. The following keys were used:
- "speaker_id" is the speaker’s identification number;
- "speaker_gender" is the speaker’s gender;
- “phrase_id” is the phrase number for the current speaker;
- “ sentence” is textual transcription;
- "sentence_lat" is textual transcription with transliteration of Cyrillic into Latin, indicated with brackets and the tag “rus”;
- “ duration” is duration of the phrase;
- “num_kar” is the number of words in Karelian;
- “num_rus” is the number of words in Russian;
- "num_rus_kar" is the number of words with intra-word code-switching;
- “num_total” is the total number of words in a phrase;
- "quality" is the recording’s quality mark.
