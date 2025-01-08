# Hybrid Post-quantum Key Agreement SM2-MLKEM for TLSv1.3

Nowadays, quantum computing is becoming a reality. This threatens the security of current cryptography algorithms.

IETF has paid lots of attention in the application of post-quantum cryptography (abbr. as PQC) in some area, including TLS protocol and so forth.

Meanwhile in China, the SM algorithms are also being mandatory applied due to compliance considerations.

The repository hosts the IETF Internet-Draft (I-D) of a hybrid approach of key exchange combining SM algorithm and FIPS ML-KEM
in TLSv1.3 and related helper documentation/tools.

This I-D defines a hybrid key exchange method CurveSM2-MLKEM, which is effectivley a new type of TLS supported group item.

It's appreciated to have more organizations as well as individuals to co-operate on this I-D.

## The Draft

Following what IETF requires, the draft's named as: [draft-yang-tls-hybrid-sm2-mlkem](https://tools.ietf.org/doc/draft-yang-tls-hybrid-sm2-mlkem)

TODO: update the links after the draft is submitted to IETF....

Reference to different formats of the compiled draft:

* [TXT](https://tools.ietf.org/id/draft-yang-tls-tls13-sm-suites-00.txt)
* [HTML](https://tools.ietf.org/html/draft-yang-tls-tls13-sm-suites-00)

Data Tracker on IETF: [https://datatracker.ietf.org/doc/draft-yang-tls-tls13-sm-suites/](https://datatracker.ietf.org/doc/draft-yang-tls-tls13-sm-suites/)

## Participation

Both the official IETF [TLS WG mailing list](https://www.ietf.org/mailman/listinfo/tls) and the [Issues](https://github.com/alipay/tls13-sm-spec/issues) section of this repository would be nice places for any comments or discussions.

## Build the Draft

Read the [BUILD.md](./BUILD.md) file for information on directory layout and building method.
