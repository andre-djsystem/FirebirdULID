## FirebidULID
<img alt="logo.png" src="https://github.com/ulid/spec/blob/master/logo.png?raw=true" heigth="200" width="100">
Universally Unique Lexicographically Sortable Identifier procedure for Firebird

## Why ULID?

* 128-bit compatibility with UUID
* 1.21e+24 unique ULIDs per millisecond
* Lexicographically sortable!
* Canonically encoded as a 26 character string, as opposed to the 36 character UUID
* Uses Crockford's base32 for better efficiency and readability (5 bits per character)
* Case insensitive
* No special characters (URL safe)

For more information, check out [ULID's README](https://github.com/ulid/spec/blob/master/README.md).

## ⚡️ Quickstart

```Firebird
SELECT ULID FROM CREATE_ULID; // 01J0XP5ZERBF4WXRNJJBX9GNYF
```

## ⚠️ License
`FirebirdULID` is free and open-source licensed under the [MIT License](https://github.com/andre-djsystem/LazJWT/blob/main/LICENSE).
