
# Find Pitch Contour

In this project, we will process the following sentence spoken in both English and Persian:

"In many examples that we discuss in this book, it is necessary to change the sampling rate of a discrete-time signal."

"در بسیاری از مثال‌هایی که در این کتاب به آن‌ها پرداخته‌ایم، تغییر نرخ نمونه‌برداری از یک سیگنال زمان گسسته ضروری است."

(page 47, line5)

The English voice is stored in a file named `voice-en.mp3` and the Persian voice is in `voice-fa.mp3`.

Our goal is to obtain the pitch contour of these voice signals using three different methods:

1. Average Magnitude Difference Function (AMDF)
2. Autocorrelation
3. Cepstrum

## Analysis

Looking at the pitch contours, we can observe several interesting patterns:

### Method Comparison

- The AMDF and Autocorrelation methods provide similar pitch contours, as both methods are based on the principle of comparing the signal to a delayed version of itself.
- The Cepstrum method, however, provides a different perspective on the pitch contour. This is because it operates in the cepstral domain, which provides a measure of the rate of change in different frequency components of the signal.

### Language Comparison

- The English and Persian voices show different pitch contour patterns. This is likely due to differences in the phonetic and prosodic properties of the two languages. For example, Persian has a different set of phonemes compared to English, which may result in different pitch patterns.

### Understanding the Results

- The pitch contours show that the speaker's pitch varies over time, indicating changes in prosody (the rhythm and intonation of speech). This variation is a key aspect of natural speech and can convey additional information beyond the words themselves, such as the speaker's emotional state or emphasis on certain words.
