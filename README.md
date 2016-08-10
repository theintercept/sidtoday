# SIDtoday Files

*SIDtoday* is the internal newsletter for the NSA's most important division, the Signals Intelligence Directorate. After editorial review, *The Intercept* is releasing nine year's worth of newsletters in batches, starting with 2003.

You can read our *SIDtoday* reporting and browse the documents online [here](https://theintercept.com/snowden-sidtoday).

This repository contains *SIDtoday* articles released by *The Intercept*, in PDF format and organized by year. We will continue to update it with new documents.

## Downloading and verifying

You can download all of the documents release so far as a zip file [here](https://github.com/firstlookmedia/sidtoday/archive/master.zip).

Every commit in this repository is cryptographically signed using PGP. If you'd like to verify the integrity of the documents, you can either use [GitHub's interface](https://github.com/blog/2144-gpg-signature-verification), or you can manually verify the signatures like this:

```sh
# Download the signing keys
gpg --recv-keys "927F419D7EC82C2F149C1BD1403C2657CD994F73"
gpg --recv-keys "6C577D0B6ABD6AF3D513EF47A72F3B3D3E45FD67"

# Clone the git repository
git clone https://github.com/firstlookmedia/sidtoday.git
cd sidtoday

# Verify the signatures on each commit
git log --show-signature
```
