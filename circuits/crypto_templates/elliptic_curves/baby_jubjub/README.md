# `baby_jubjub`

This folder contains the templates to do operations on [Baby Jubjub](https://github.com/ethereum/EIPs/pull/2494) elliptic curve.

## Structure of the folder

- [`edwards`](edwards)
    - [`babyadd`](edwards/babyadd)
    - [`babycheck`](edwards/babycheck)
    - [`babydbl`](edwards/babydbl)
    - [`babypbk`](edwards/babypbk)
    - [`scalar_mul`](edwards/scalar_mul)
        - [`scalarmul`](edwards/scalar_mul/scalarmul)
        - [`scalarmulany`](edwards/scalar_mul/scalarmulany)
        - [`scalarmulfix`](edwards/scalar_mul/scalarmulfix)
        - [`scalarmulwtable`](edwards/scalar_mul/scalarmulwtable)
- [`edwards2montgomery`](edwards2montgomery)
- [`montgomery`](montgomery)
    - [`montgomeryadd`](montgomery/montgomeryadd)
    - [`montgomerydouble`](montgomery/montgomerydouble)
- [`montgomery2edwards`](montgomery2edwards)
- [`point2bits`](point2bits)

## Background on Baby Jubjub