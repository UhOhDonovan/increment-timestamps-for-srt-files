# Simple Subtitle Incrementer for .srt Files

This is a simple jupiter notebook that I made to fix an issue with handbrake where it extracts the subtitles of a movie out of sync with the video and audio. All it does is take an srt ("subtitle") file, regexes the time stamp on the subtitle line, and increments them by "N" seconds. It then writes the newly resynced subtitle file to the project root.