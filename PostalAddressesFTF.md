Draft: Instead of using direct references to a postal address to reach a given person, use indirection and mailing tables. 

- Bob lives at : Postal Address A
- Bob registers as : Mailing Address Bob #1234 ↦ Postal Address A for Bob
- Alice lives at : Postal Address B
- Alice registers as : Mailing Address Alice #4321 ↦ Postal Address B for Alice
- Bob mails to : Mailing Address Alice #4321 -- and not to Postal Address B -- to reach Alice at Postal Address B
- Alice moves to : Postal Address C
- Alice registers as : Mailing Address Alice #4321 ↦ Postal Address C for Alice
- Bob mails to : Mailing Address Alice #4321 -- again -- which is the fun part because it will be delivered to Alice at Postal Address C
