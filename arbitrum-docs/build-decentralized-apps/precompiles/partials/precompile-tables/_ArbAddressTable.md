<table>
  <thead>
    <tr>
      <th>Method</th>
      <th>Solidity interface</th>
      <th>Go implementation</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>
        <code>addressExists(address addr)</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/1cab72ff3dfcfe06ceed371a9db7a54a527e3bfb/src/precompiles/ArbAddressTable.sol#L17"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v2.3.3/precompiles/ArbAddressTable.go#L17"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>AddressExists checks if an address exists in the table</td>
    </tr>
    <tr>
      <td>
        <code>compress(address addr)</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/1cab72ff3dfcfe06ceed371a9db7a54a527e3bfb/src/precompiles/ArbAddressTable.sol#L24"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v2.3.3/precompiles/ArbAddressTable.go#L22"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Compress and returns the bytes that represent the address</td>
    </tr>
    <tr>
      <td>
        <code>decompress(bytes calldata buf, uint256 offset)</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/1cab72ff3dfcfe06ceed371a9db7a54a527e3bfb/src/precompiles/ArbAddressTable.sol#L32"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v2.3.3/precompiles/ArbAddressTable.go#L27"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>
        Decompress the compressed bytes at the given offset with those of the corresponding account
      </td>
    </tr>
    <tr>
      <td>
        <code>lookup(address addr)</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/1cab72ff3dfcfe06ceed371a9db7a54a527e3bfb/src/precompiles/ArbAddressTable.sol#L41"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v2.3.3/precompiles/ArbAddressTable.go#L40"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Lookup the index of an address in the table</td>
    </tr>
    <tr>
      <td>
        <code>lookupIndex(uint256 index)</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/1cab72ff3dfcfe06ceed371a9db7a54a527e3bfb/src/precompiles/ArbAddressTable.sol#L47"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v2.3.3/precompiles/ArbAddressTable.go#L52"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>LookupIndex for an address in the table by index</td>
    </tr>
    <tr>
      <td>
        <code>register(address addr)</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/1cab72ff3dfcfe06ceed371a9db7a54a527e3bfb/src/precompiles/ArbAddressTable.sol#L54"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v2.3.3/precompiles/ArbAddressTable.go#L67"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Register adds an account to the table, shrinking its compressed representation</td>
    </tr>
    <tr>
      <td>
        <code>size()</code>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro-contracts/blob/1cab72ff3dfcfe06ceed371a9db7a54a527e3bfb/src/precompiles/ArbAddressTable.sol#L59"
          target="_blank"
        >
          Interface
        </a>
      </td>
      <td>
        <a
          href="https://github.com/OffchainLabs/nitro/blob/v2.3.3/precompiles/ArbAddressTable.go#L73"
          target="_blank"
        >
          Implementation
        </a>
      </td>
      <td>Size gets the number of addresses in the table</td>
    </tr>
  </tbody>
</table>