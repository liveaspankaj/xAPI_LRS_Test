Experience API LRS Test
=============

## Policies and Procedures for Conformance Testing Group:

### Goal

This group exists to create a single conformance test to be used as the official Experience API 
(xAPI) v1.0.1 conformance test.  This test will have the backing of the Advanced Distributed 
Learning (ADL) Initiative.

### Conformance Test Scope

* The conformance test will test ONLY an LRS and test ONLY mandatory requirements within the xAPI Specification.
* An LRS that passes this conformance test can and should be used to test conformance of content/clients of xAPI.
* All tests must be passed to achieve conformance, as opposed to “passing” all requirements in the TR document (these should be the same, but conformance is driven by the test results)
* It is anticipated that additional Unit Tests for communities of practice may be created, such as for CMI5.  Those collections of Unit Tests can be included in this group, but are not part of the conformance endorsed by ADL.

### Conformance Testing Requirments Document

* All conformance requirements will be listed in the Testing Requirements (TR) document in a means which tests/documents can refer to a specific requirement number.
* All conformance requirements in the TR document will link directly to the specification by section and requirement # within that section.
* The end goal is to have a direct mapping of every TR requirement to the specification document, however it is anticipated that some indirect mappings or changes to the specification itself may be necessary.
* An example of an indirect mapping would be a requirement imposed on a Statement but not on an LRS to validate a Statement in that way.  Clearly the intention is for the LRS to validate conformance in this case, but may not have been explicitly mentioned.


### Process 

* The group will work to create the TR document and test cases, which will be called Unit Tests.
* The group will use current Unit Tests to create a process for new Unit Tests.
* In the event of a requirement needed in the TR, but does not show up in the spec document, an issue will be created within the specification group.
* Differing TR expectations must have group consensus before bringing a change to the specification group.
* After the TR document is complete, the specification will be examined for requirements not referenced by the TR document.
* Another post-TR document thing to look at is LRS to LRS Statement transfer and if specific requirements are needed.

### Unit Tests

* Every TR will have one or more unit test associated with it.  
* Unit Tests and the TR will reference each other, as opposed to the TR document to specification references, which only go one way.
* There may be more than one Unit Test that references the same TR document entry.
* Unit Tests may only test things referenced within the TR document.
* Issues can be opened within this group to perform gap analysis on whether what the Unit Test is testing should be a part of the TR document.  This will most commonly occur on existing Unit Tests as they migrate into this effort.
* All Unit Tests upon being run must explicitly state if they pass or fail, and if there is a failure, refer to the exact requirement that has failed via the TR document numbering system.
