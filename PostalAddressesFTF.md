Draft: Instead of using direct references to a postal address to reach a certain person, use indirection and mailing tables addresses. 

- Bob lives at : Postal Address A
- Bob registers as : Mailing Address Bob #1234 ↦ Postal Address A
- Alice lives at : Postal Address B
- Alice registers as : Mailing Address Alice #4321 ↦ Postal Address B
- Bob mails to : Mailing Address Alice #4321 -- and not to Postal Address B -- to reach Alice at Postal Address B
- Alice moves to : Postal Address C
- Alice registers as : Mailing Address Alice #4321 ↦ Postal Address C
- Bob mails to : Mailing Address Alice #4321 -- again -- which is the fun part because it will be delivered to Postal Address C -- this is *basic* indirection
