# turing-machine

1. Exanple of instruction:

{
    "s1": {
        "0": ["s1", "0", "R"],
        "1": ["s1", "1", "R"],
        "B": ["s2", "B", "L"]
    },
    "s2": {
        "0": ["s3", "1", "L"],
        "1": ["s2", "0", "L"],
        "B": ["s3", "1", "L"]
    },
    "s3": {
        "0": ["s3", "0", "L"],
        "1": ["s3", "1", "L"],
        "B": ["sh", "B", "R"]
    }
}

2. Example of initialization head setting:

s1 0

3. Tape field example write with spaces like this:

1 0 1 1 0 1

