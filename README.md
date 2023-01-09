# Specs

BitsApp specifications (BAS in short) stand for **BitsApp Implementation Specifications**. Specs are written to provide open and accessible documentation for [BitsApp](https://bits.app) implementation details.

- [BAS-01: One-directional channels](01.md)
- [BAS-02: Expiring channel addresses](02.md)
- [BAS-03: Expiring channel formation protocol](01.md)
- [BAS-04: Silent swaps](03.md)
- [BAS-05: Swap factories](04.md)
- [BAS-06: Swap formation protocol](05.md)
- [BAS-07: Swap credit protocol](06.md)
- [BAS-08: Swap settlement protocol](07.md)
- [BAS-09: Swap statuses](08.md)
- [BAS-10: Payment statuses](09.md)
- [BAS-11: Interactive swap invoices](10.md)
- [BAS-12: Non-interactive swap invoices](11.md)
- [BAS-13: Permenant channel addresses](12.md)
- [BAS-14: Encumbered swap factories](13.md)
- [BAS-15: Inbound swap settlement protocol](14.md)
- [BAS-16: Swap factory trees](15.md)
- [BAS-17: Swap settlement credits](16.md)
- [BAS-18: Channel backups](17.md)
- [BAS-19: Channel recovery](18.md)
- [BAS-20: Swap service](19.md)
- [BAS-21: Routing service](20.md)
- [BAS-22:  Service provider federation](21.md)

## Spec Categorization

### Onboarding
| Index  | Specification                                      | Status     |
|------- |----------------------------------------------------|------------|
| [BAS-01](01.md)   | One-directional channels                | Draft      |
| [BAS-02](02.md)   | Expiring channel addresses              | Draft      |
| [BAS-03](03.md)   | Expiring channel formation prototocol   | Draft      |

### Receiving
| Index  | Specification                                      | Status     |
|------- |----------------------------------------------------|------------|
| [BAS-04](04.md)   | Silent swaps                            | Draft      |
| [BAS-05](05.md)   | Swap factoriees                         | Draft      |
| [BAS-06](06.md)   | Swap formation protocol                 | Draft      |
| [BAS-07](07.md)   | Swap credit protocol                    | Draft      |
| [BAS-08](08.md)   | Swap settlement protocol                | Draft      |

### User Experience
| Index  | Specification                                      | Status     |
|------- |----------------------------------------------------|------------|
| [BAS-09](09.md)   | Swap statusses                          | Draft      |
| [BAS-10](10.md)   | Payment statusses                       | Draft      |
| [BAS-11](11.md)   | Interactive swap invocies               | Draft      |
| [BAS-12](12.md)   | Non-interactive swap invoices           | Draft      |

### Future Extensions
| Index  | Specification                                      | Status     |
|------- |----------------------------------------------------|------------|
| [BAS-13](13.md)   | Permenant channel addresses             | Draft      |
| [BAS-14](14.md)   | Encumbered swaps factories              | Draft      |
| [BAS-15](15.md)   | Inbound swap settlement protocol        | Draft      |
| [BAS-16](16.md)   | Swap factory trees                      | Draft      |
| [BAS-17](17.md)   | Swap settlement credits                 | Draft      |

### Backups & Recovery
| Index  | Specification                                      | Status     |
|------- |----------------------------------------------------|------------|
| [BAS-18](18.md)   | Channel backups                         | Draft      |
| [BAS-19](19.md)   | Channel recovery                        | Draft      |

### Service
| Index  | Specification                                      | Status     |
|------- |----------------------------------------------------|------------|
| [BAS-20](20.md)   | Swap service                            | Draft      |
| [BAS-21](21.md)   | Routing service                         | Draft      |
| [BAS-22](22.md)   | Service provider federation             | Draft      |

Please update these lists when proposing NIPs introducing new event kinds.

When experimenting with kinds, keep in mind the classification introduced by [NIP-16](16.md).

## Criteria for acceptance of NIPs

1. They should be implemented in at least two clients and one relay -- when applicable.
2. They should make sense.
3. They should be optional and backwards-compatible: care must be taken such that clients and relays that choose to not implement them do not stop working when interacting with the ones that choose to.
4. There should be no more than one way of doing the same thing.
5. Other rules will be made up when necessary.

## License
