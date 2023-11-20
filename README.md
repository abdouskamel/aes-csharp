# AES-128, AES-192 and AES-256 in C#

This is provided only for educational purposes and is not intended to be a fast and production-ready AES implementation.

The version of AES to use is chosen based on the size of the key provided.

See folder `example` for how to use the code to cipher streams.

## Code Structure

- The class `AESCipher` is defined in four files: `aeskeygen.cs`, `aescipher.cs`, `aesdecipher.cs`, and `aesconsts.cs`.
- `aeskeygen.cs`defines the property `MainKey` which represents the AES key.
- `aescipher.cs` and `aesdecipher.cs` define the cipher and decipher methods.
- `aesconsts.cs` defines static tables used by the AES algorithm.
- `Helpers` defines low-level byte operations on byte arrays.