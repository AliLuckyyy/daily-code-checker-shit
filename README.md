# daily-code-checker-shit {
  "analysisRequestId": 2112,
  "id": 23548,
  "observations": [
    {
      "analysisId": 23548,
      "confidence": "HIGH",
      "endColumn": null,
      "endLine": 1,
      "id": 208382,
      "message": "Found error: Full Inliner Non Expression Split Argument Evaluation Order. Compiler 0.8.0 may introduce bugs.. undefined",
      "recommendation": "Please upgrade to a version without these issues.",
      "severity": "low",
      "sourcePath": "/source-1715617978391.sol",
      "startColumn": null,
      "startLine": 1,
      "swcId": "TMR-003",
      "title": "Outdated Compiler Version",
      "vulnerabilityId": null
    },
    {
      "analysisId": 23548,
      "confidence": "HIGH",
      "endColumn": null,
      "endLine": 1,
      "id": 208383,
      "message": "Found error: Missing Side Effects On Selector Access. Compiler 0.8.0 may introduce bugs.. undefined",
      "recommendation": "Please upgrade to a version without these issues.",
      "severity": "low",
      "sourcePath": "/source-1715617978391.sol",
      "startColumn": null,
      "startLine": 1,
      "swcId": "TMR-003",
      "title": "Outdated Compiler Version",
      "vulnerabilityId": null
    },
    {
      "analysisId": 23548,
      "confidence": "HIGH",
      "endColumn": null,
      "endLine": 1,
      "id": 208384,
      "message": "Found error: Abi Reencoding Head Overflow With Static Array Cleanup. Compiler 0.8.0 may introduce bugs.. undefined",
      "recommendation": "Please upgrade to a version without these issues.",
      "severity": "low",
      "sourcePath": "/source-1715617978391.sol",
      "startColumn": null,
      "startLine": 1,
      "swcId": "TMR-003",
      "title": "Outdated Compiler Version",
      "vulnerabilityId": null
    },
    {
      "analysisId": 23548,
      "confidence": "HIGH",
      "endColumn": null,
      "endLine": 1,
      "id": 208385,
      "message": "Found error: Dirty Bytes Array To Storage. Compiler 0.8.0 may introduce bugs.. undefined",
      "recommendation": "Please upgrade to a version without these issues.",
      "severity": "low",
      "sourcePath": "/source-1715617978391.sol",
      "startColumn": null,
      "startLine": 1,
      "swcId": "TMR-003",
      "title": "Outdated Compiler Version",
      "vulnerabilityId": null
    },
    {
      "analysisId": 23548,
      "confidence": "HIGH",
      "endColumn": null,
      "endLine": 1,
      "id": 208386,
      "message": "Found error: Data Location Change In Internal Override. Compiler 0.8.0 may introduce bugs.. undefined",
      "recommendation": "Please upgrade to a version without these issues.",
      "severity": "low",
      "sourcePath": "/source-1715617978391.sol",
      "startColumn": null,
      "startLine": 1,
      "swcId": "TMR-003",
      "title": "Outdated Compiler Version",
      "vulnerabilityId": null
    },
    {
      "analysisId": 23548,
      "confidence": "HIGH",
      "endColumn": null,
      "endLine": 1,
      "id": 208387,
      "message": "Found error: Nested Calldata Array Abi Reencoding Size Validation. Compiler 0.8.0 may introduce bugs.. undefined",
      "recommendation": "Please upgrade to a version without these issues.",
      "severity": "low",
      "sourcePath": "/source-1715617978391.sol",
      "startColumn": null,
      "startLine": 1,
      "swcId": "TMR-003",
      "title": "Outdated Compiler Version",
      "vulnerabilityId": null
    },
    {
      "analysisId": 23548,
      "confidence": "HIGH",
      "endColumn": null,
      "endLine": 1,
      "id": 208388,
      "message": "Found error: Signed Immutables. Compiler 0.8.0 may introduce bugs.. undefined",
      "recommendation": "Please upgrade to a version without these issues.",
      "severity": "low",
      "sourcePath": "/source-1715617978391.sol",
      "startColumn": null,
      "startLine": 1,
      "swcId": "TMR-003",
      "title": "Outdated Compiler Version",
      "vulnerabilityId": null
    },
    {
      "analysisId": 23548,
      "confidence": "HIGH",
      "endColumn": null,
      "endLine": 1,
      "id": 208389,
      "message": "Found error: A B I Decode Two Dimensional Array Memory. Compiler 0.8.0 may introduce bugs.. undefined",
      "recommendation": "Please upgrade to a version without these issues.",
      "severity": "low",
      "sourcePath": "/source-1715617978391.sol",
      "startColumn": null,
      "startLine": 1,
      "swcId": "TMR-003",
      "title": "Outdated Compiler Version",
      "vulnerabilityId": null
    },
    {
      "analysisId": 23548,
      "confidence": "HIGH",
      "endColumn": null,
      "endLine": 1,
      "id": 208390,
      "message": "Found error: Keccak Caching. Compiler 0.8.0 may introduce bugs.. undefined",
      "recommendation": "Please upgrade to a version without these issues.",
      "severity": "low",
      "sourcePath": "/source-1715617978391.sol",
      "startColumn": null,
      "startLine": 1,
      "swcId": "TMR-003",
      "title": "Outdated Compiler Version",
      "vulnerabilityId": null
    },
    {
      "analysisId": 23548,
      "confidence": "HIGH",
      "endColumn": null,
      "endLine": 1,
      "id": 208391,
      "message": "Found error: Floating pragma: ^0.8.0. Floating pragma detected: ^0.8.0. Floating pragmas can introduce a backwards compatibility risk that can lead to contracts behaving differently than intended.",
      "recommendation": "It is recommended to lock the version of the Solidity compiler to the specific version you are using.",
      "severity": "informational",
      "sourcePath": "/source-1715617978391.sol",
      "startColumn": null,
      "startLine": 1,
      "swcId": "TMR-004",
      "title": "Floating Pragma",
      "vulnerabilityId": null
    },
    {
      "analysisId": 23548,
      "confidence": "MEDIUM",
      "endColumn": null,
      "endLine": 5,
      "id": 208392,
      "message": "Found error: block.timestamp in getToday. Found 1 time-related warnings:. Using block values like 'block.timestamp' and 'block.number' as a proxy for time is risky as they are not precise and can be manipulated to some extent.",
      "recommendation": "It's recommended to use oracles or other external time services for more precise time-keeping.",
      "severity": "medium",
      "sourcePath": "/source-1715617978391.sol",
      "startColumn": null,
      "startLine": 4,
      "swcId": "TMR-017",
      "title": "Block values as a proxy for time",
      "vulnerabilityId": null
    },
    {
      "analysisId": 23548,
      "confidence": "HIGH",
      "endColumn": null,
      "endLine": 5,
      "id": 208393,
      "message": "Found error: Inline Assembly in getToday. Found 2 potential inline assembly usage instance(s).. The use of inline assembly can be dangerous and error-prone. Incorrect use of inline assembly can introduce severe vulnerabilities, allowing attackers to execute arbitrary code and manipulate contract state or logic. Especially when handling function pointers, or any critical state variables, extreme caution is required.",
      "recommendation": "Avoid using inline assembly when possible. Use Solidity's high-level constructs which are safer and less prone to errors. When the use of inline assembly is unavoidable, make sure to carefully review and test the assembly code. Also, consider using well-vetted libraries and tools and getting your code audited by security professionals.",
      "severity": "informational",
      "sourcePath": "/source-1715617978391.sol",
      "startColumn": null,
      "startLine": 4,
      "swcId": "TMR-028",
      "title": "Arbitrary Jump with Function Type Variable",
      "vulnerabilityId": null
    },
    {
      "analysisId": 23548,
      "confidence": "HIGH",
      "endColumn": null,
      "endLine": 5,
      "id": 208394,
      "message": "Found error: Inline Assembly in getToday. Found 2 potential inline assembly usage instance(s).. The use of inline assembly can be dangerous and error-prone. Incorrect use of inline assembly can introduce severe vulnerabilities, allowing attackers to execute arbitrary code and manipulate contract state or logic. Especially when handling function pointers, or any critical state variables, extreme caution is required.",
      "recommendation": "Avoid using inline assembly when possible. Use Solidity's high-level constructs which are safer and less prone to errors. When the use of inline assembly is unavoidable, make sure to carefully review and test the assembly code. Also, consider using well-vetted libraries and tools and getting your code audited by security professionals.",
      "severity": "informational",
      "sourcePath": "/source-1715617978391.sol",
      "startColumn": null,
      "startLine": 4,
      "swcId": "TMR-028",
      "title": "Arbitrary Jump with Function Type Variable",
      "vulnerabilityId": null
    },
    {
      "analysisId": 23548,
      "confidence": "HIGH",
      "endColumn": null,
      "endLine": 5,
      "id": 208395,
      "message": "Found error: getToday. Found 1 unprotected functions using RBAC:. Unprotected functions using RBAC can lead to unauthorized access.",
      "recommendation": "Review the functions to ensure they have the appropriate access controls applied.",
      "severity": "informational",
      "sourcePath": "/source-1715617978391.sol",
      "startColumn": null,
      "startLine": 4,
      "swcId": "TMR-038",
      "title": "Unprotected Functions Using RBAC",
      "vulnerabilityId": null
    }
  ],
  "tool": {
    "displayName": "Scout Scan"
  }
}
