# Umm al-Qura reference-policy investigation, 27 October 2026

No arbitrary table substitution was made. The maintained AH 1300–1600 table is ICU-compatible. All 2,196 month starts in an independently published dataset attributed to a current KACST-service harvest agree with the existing provider over AH 1318–1500. Its source is https://github.com/AsimNet/ummulqura-calendar/blob/main/src/Data/MonthStarts.php .

That does not settle primary authority: direct requests to the Saudi government site/service were unavailable during this investigation. HijriDate's publication-based dataset still disagrees with the maintained table on the 22,058 dates identified in the first audit, including some future years. This is a provenance/revision-policy conflict, not evidence that either source should silently overwrite the other. The independently published harvest may itself derive from the same underlying data; it is corroboration, not a substitute for live primary verification.

`make audit-authorities` deliberately continues to fail the three recorded HijriDate comparison cases. Build, internal arithmetic, formatting and navigation checks pass for the declared maintained table. Full historical/official-date accuracy is not certified until this source conflict is resolved.

See also https://hijridate.readthedocs.io/en/stable/background.html for that project's account of printed-calendar and KACST sources. Contemporary printed almanacs and retrospective reconstructions can differ; the observed future-year disagreement also remains explicit.
