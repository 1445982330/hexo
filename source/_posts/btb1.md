---
title: 区块链机考
date: 2023-02-18
---
```1
// SPDX-License-Identifier: GPL-3.0
pragma solidity >=0.7.0 <0.9.0;

```

```2
contract Contract {
    function main(int256 a, int256 b) public pure returns (int256) {
        return a + b;
    }
}

```

```3
contract Contract {
    int256 _v;
    function set(int256 v) public {
        _v = v;
    }
    function get() public view returns(int256) {
        return _v;
    }
}

```

```4
contract Contract {
    event result(int256);
    function main(int256 a, int256 b) public {
        emit result(a * b);
    }
}

```

```5
contract Contract {
    function main() public pure returns(string memory) {
        return "Hello,World!";
    }
}

```

```6
contract Contract {
    int256 _v = 0;
    function add(int256 v) public {
        _v += v;
    }
    function get() public view returns(int256) {
        return _v;
    }
}

```

```7
contract Contract {
    int256[] arr;
    function push(int256 v) public {
        arr.push(v);
    }
    function last() public view returns(int256) {
        return arr[arr.length-1];
    }
}

```
