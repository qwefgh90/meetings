# WebAssembly W3C Process

이 파일은 기능 제안이 표준화 절차에서 어떻게 이뤄지는지 나타낸다.

This file describes how feature proposals will progress through
the standardization process.

기능은 웹 어셈블리에 상당히 큰 변화이다. such that it for example
requires additional opcodes, types, tests, or module sections.
See case #3 [here](consensus.md).

A feature is a substantial change to WebAssembly, such that it for example
requires additional opcodes, types, tests, or module sections.
See case #3 [here](consensus.md).

다음과 같은 것이 기능이다.:

  * Adds an opcode or other pieces of abstract syntax
  * Changes or extends the binary format
  * Changes or extends the text format
  * Requires adding or changing tests
  * Requires extending or changing the reference interpre
  
Something is definitely a feature if it:

  * Adds an opcode or other pieces of abstract syntax
  * Changes or extends the binary format
  * Changes or extends the text format
  * Requires adding or changing tests
  * Requires extending or changing the reference interpreter

wasm 선언문에 맞지 않거나 오히려 선언문 수정할 정도의 제안이 아니라면 기능으로 분류하지 않는다.

Something is out-of-scope if it doesn't fit the [WebAssembly Working Group's charter](https://www.w3.org/2017/08/wasm-charter) and there's agreement that the charter should not be amended to cover the proposal.

일번적으로 표준화 프로세스는 일련의 단계를 거친다. 그러나 이슈가 발견되거나, 합의사항이 의존적일 경우 제안들은 이전 단계로 돌아가야 한다.

In general, the process moves forward through a series of numbered phases.
However, if issues are uncovered or consensus devolves,
proposals should back up to the appropriate prior step.

## 0. 사전 제안 [개인 기여자]

제출 요구사항:

  * 커뮤니티 그룹 구성원 아디이어를 가지고 있다. 어떠한 커뮤니티 그룹 투표가 요구되지 않는다.
  
이 단계는 다음과 같이 진행된다.

  1. 특정 아이디어에 대한 이슈는 [설계 프로젝트](https://github.com/WebAssembly/design/issues)에 저장된다.
  1. 기능에 대한 토론이 이슈에서 이뤄진다.
  1. 제안 주도자가 나타난다. 제안 주도자들은 제안을 [제안 목록](https://github.com/WebAssembly/proposals/blob/master/README.md)에 추가할 것이다.
  1. 주도자는 기능에 대한 형식적인 설명을 이슈나 별도 프로젝트에 작성할 것이다.
  1. [격주로 열리는 화장 전화](https://github.com/WebAssembly/meetings/) 회의 주제 중 하나로 추가된다. 이는 Pull request을 활용한다.
  1. 이 제안에 대한 일반적인 관심에 대해 투표합니다. 합의 요구사항들은 적다.: 커뮤니티 구성원들은 이 기능이 프로젝트의 범위 안에 있는지 그럴싸하게 동작할 것이라 믿는지? 정도만 확인한다.
  
## 0. Pre-Proposal [Individual Contributor]

Entry requirements:

  * A Community Group member has an idea. Notably, no CG vote is required to begin phase 0.

During this phase:

  1. An issue is filed on the [design repository](https://github.com/WebAssembly/design/issues) to present the idea.
  1. Discussion on the feature occurs on the issue.
  1. A champion or champions emerge. They may add the proposal to the [proposal list](https://github.com/WebAssembly/proposals/blob/master/README.md) at phase 0.
  1. The champion(s) put together a somewhat-formal description of the feature in their own GitHub repository or on the issue.
  1. An item is added to the [bi-weekly Community Group video calls](https://github.com/WebAssembly/meetings/)'s agenda through a pull request.
  1. The CG votes on general interest in this proposal. Consensus requirements are low: do members believe that the feature is in-scope and will plausibly be workable?

## 1. Feature Proposal [Community Group]

Entry requirements:

  * The pre-proposal vote has succeeded.

During this phase:

  1. If the proposal is not already listed, it should be added to the [proposal list](https://github.com/WebAssembly/proposals/blob/master/README.md) at this time.
  1. A new repository, forking the spec repo, is created by one of the WebAssembly organization administrators, or transfered to the WebAssembly organization by the champion.
  1. The champion will attempt to reach broad consensus in the Community Group.
  1. Pull requests and issues are used to iterate on the design of the feature. Specifically, the spec text must be in a reasonably complete state before attempting to move to phase 2.
  1. If relevant to demonstrate the viability of a feature, prototype implementations of the feature are implemented by interested embedders (possibly on a branch).

## 2. Proposed Spec Text Available [Community + Working Group]

Entry requirements:

   * Full proposed English spec text available in a forked repo around which a reasonably high level of consensus exists.
   * *Updates to the formal notation, test suite, and reference interpreter are NOT yet required.*

During this phase:

   * One or more implementations proceed on prototyping the feature to the point that a comprehensive set of tests can be added.
   * A test suite is added. These tests need not pass the reference interpreter at this point, but should pass on some implementation.

## 3. Implementation Phase [Community + Working Group]

Entry requirements:

   * Test suite has been updated to cover the feature in its forked repo.
   * The test suite should run against some implementation, though it need not be
     the reference interpreter.
   * *Formal notation in the spec need not be updated.*

During this phase, the following proceeds in parallel:

  * Embedders implement the feature.
  * The forked repo is updated to include revisions to the formalization.
  * The forked repo spec is updated to include implementation of the feature
    in the reference interpreter.
  * The feature is implemented in toolchains.

## 4. Standardize the Feature [Working Group]

Entry requirements:

   * Two or more Web VMs implement the feature.
   * At least one toolchain implements the feature.
   * The formalization and the reference interpreter are usually updated
     (though these two can be done as part of step 3 at the Working Group
      chair's discretion).
   * Community Group has reached consensus in support of the feature.
   * NOTE: By this point the proposal is basically frozen, since
     the Community Group is the sole venue where substantial work can occur.

At this point:

   * The feature is fully handed off to the Working Group.
   * During this phase, Working Group members discuss the feature,
     consider edge cases, and work to confirm consensus that the feature is now
     complete.
   * Periodically, the Working Group will hold polls on how "ship worthy" the feature is,
     in order to help browsers to make decisions about when to ship.
   * Only minor cosmetic changes occur at this point.
     If substantial changes are deemed required, the feature is sent back to
     the Community Group.

## 5. The Feature is Standardized [Working Group]

Entry requirements:

   * Consensus is reached in amongst Working Group members that the feature
     is complete.

When Working Group consensus is reached (online), editors can merge the feature
into master on the spec repo.
The W3C snapshots (for REC) are made at a regular cadence (in a W3C repo), used
to stamp official version. Matching tags are added in the github spec repo.


## FAQ

#### Who owns the various existing W3C repos?

They are owned in common by the Working + Community Groups. The Working Group
uses the github.com/WebAssembly/spec repo to iterate on finalized proposals
for hand-off
to the W3C's snapshotted copy of the spec. The other repos are primarily
overseen by the Community Group.

#### What about licenses?

The spec and spec forks will move to a
[W3C Software and Document Notice and
License](https://www.w3.org/Consortium/Legal/2015/copyright-software-and-document).
Other related repos for prototypes + tools will continue under their respective
licenses.

#### What is the Community Group for?

Incubation.
To provide a safe harbor for a broad set of stakeholders to discuss, design,
and iterate on new features during Steps 1-3 above.
It should attempt to address all concerns, but need not reach 100% consensus.

#### What is the Working Group for?

To finalize and ratify mostly complete specs + test suites from the Community
Group.
Changes to the spec need not have reached full consensus in the Community Group
to move to the Working Group, but key Working Group stakeholders should resolve
outstanding mismatch in the Community Group.

#### Who will have admin rights + close issues etc?

This can be distributed and handled by multiple folks.
In terms of github issues specifically, chairs will mainly step in to drive
consensus, keep discussions civil, and as a first escalation point if someone
is unhappy with how the collaboration is conducted (for instance if someone is
unhappy a particular issue was closed over their objections).
This is a general part of their role in community building:
https://www.w3.org/Guide/chair-roles
