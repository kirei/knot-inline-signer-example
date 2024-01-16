# Knot Inline Signer Example

This repository contains an example how to use Knot as a DNSSEC inline signer.

## Usage

**Start container**

    docker compose up -d

**Show signed zone**

    docker compose exec knot kdig @127.0.0.1 test.nxdomain.se axfr
