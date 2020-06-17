
# 컨센서스 결정(합의)

컨센서스는 표준을 결정하는 프로세스에서 매우 중요한 부분이다.

* 컨센서스를 형성하는 것은 각 전문가들이 더욱 자신있게 제안 할 수 있도록 도와준다.
* 컨센서스는 불필요하게 했던 토론을 다시 하는 것을 막아준다. (단, 다시 토론해야 될정도로 변경이 많지 않을때)
* 만약 구성원이 자신의 목소리가 잘 전달이 안된다고 생각하기 시작하면 표준을 만드는 작업 그대로 멈출 수 있으므로 
  찬반에 대해 기록하는 것 역시 컨센서스를 만드는데에 매우 중요한 작업이다.

## 대면 회의 합의 절차

대면 회의를 할때 각 전문가들은 합의점을 제시해야하며 의논하는 과정에서 새로운 합의점들이 추가될 수 있다. 

합의는 다음 절차를 따른다:

1. 전문가는 모두가 눈으로 직접 읽을 수 있는 형식으로 질문을 한다. 
   여러개의 합의점이 제시된 이후 투표에 붙여질 수 있다.
2. 의장은 모든 참석자에게 질문에 대한 의견을 듣는다. 
   그리고 투표를 진행하며 완전 찬성, 찬성, 중립, 반대, 완전 반대, 기권 중 하나를 선택할 수 있다.
   서기는 투표 결과를 기록한다.
3. 필요한 경우 의장은 몇몇 사람에게 왜 그들이 그런 선택을 했는지 물을 수 있다.
4. 의장은 합의가 종료되었는지 결정할 수 있다.
5. 참석자는 결정에 대한 공식적인 반대 의사를 표명할 수 있다. 
   반대한 사람은 기술적으로 반대하는 이유를 설명해야하며 새로운 제안을 해야한다.
   이러한 제안은 모호하거나 불완전할 수 있다. 주의사항: 워킹 그룹에서 
   공식적인 반대는 W3C Director에 의해 검토된다. (커뮤니티 그룹 제외)
   반대하는 이유나 이론적 해석을 말하지 않을 경우 검토 대상에서 제외될 수 있다.

합의를 위해 필요한 찬성표의 수는 정해져 있지 않다. 경우에 따라 한명의 개발자 또는 사용자에 의해 
합의가 되지 않을 수 있다. 중요한 점은 모든 참석자는 합의 절차가 잘 동작한다고 믿는 것이다.
합의위에서 다른 합의를 할 수 있도록 의장은 노력해야한다.

합의가 잘 되지 않았을 경우 더 많은 정보를 바탕으로 다시 토론을 진행할 수 있을 것이다.

쉽게 합의가 될 경우, 의장은 이의제기 요청을 간단히 받고 넘어갈 수 있다.
합의를 강제하기 위해 하나의 반대로 충분하다.

# Determining consensus

## In-person meeting consensus

There is no specific number of votes required to establish or block
consensus. In some circumstances a single implementor's or user's concerns may,
at the chair's discretion, block consensus. That being said, it is critical that
all participants believe the consensus process works! The chair must strive for
consensus on consensus.

Lack of consensus doesn't necessarily prevent an idea from being revisited
later. "More information requested" or "request more work" are acceptable
outcomes for lack of consensus.

In some cases where consensus seems to obviously have been reached, the chair
may poll a lighter-weight request for objections to unanimous consensus. A
single objection is sufficient to force the above consensus process.

------------------
For in-person meetings, champions are expected to list points for which they
will seek consensus in the meeting agenda, and new consensus points can be added
in-person as the discussion proceeds.

Polling consensus is done by the chair:

1. The champion asks a question, which is written down for all to see. Multiple
   related consensus points could be polled back-to-back, in which case they are
   all declared before polling takes place.
2. The chair asks all participants to express their opinion to the question,
   asking in turn whether they are `Strongly For`, `For`, `Neutral`, `Against`,
   or `Strongly Against`. Participants vote for a single option by raising their
   hand, or abstain entirely. Aggregate votes are recorded by the note-taker.
3. If deemed relevant, the chair can ask certain participants if their wish to
   explain their vote for the note-taker.
4. The chair determines whether consensus was reached.
5. A participant may decide to register a formal objection to the decision. An
   individual who registers a formal objection should cite technical arguments
   and propose changes that would remove the formal objection; these proposals
   may be vague or incomplete. Note: in the Working Group, formal objections are
   reviewed by the W3C Director. Such review is not guaranteed for the Community
   Group. Formal objections that do not provide substantive arguments or
   rationale are unlikely to receive serious consideration by the Director.
----------------
## Online consensus

It is critical that work progresses between in-person meetings: agreed-upon
designs need to move forward, and new ideas need to reach some level of maturity
before being discussed in-person. To that end, this group can reach consensus
online, either on GitHub repositories under the WebAssembly organization or in
official video calls. In the latter case, decisions are recorded in meeting
notes and published just like in-person meeting notes are published.

We introduce the following concepts to help the online decision process:

* Contributors of *different affiliation* are individuals who are affiliated
  with different companies or institutions.
* *Interested parties* are individuals, companies, or institutions who usually
  participate in the WebAssembly Community Group or Working Group and are
  interested in a particular topic.
* *Small group* is a subset of Community Group and Working Group participants
  who decide to collaborate on a single targeted proposal.

We differentiate the following cases:

1. Editors are empowered to make changes that have no technical impact without
   explicit group decision. GitHub issues and pull requests are
   sufficient. Their title should identify them as editorial. Closing or merging
   them after a full work day of positive review by at least one contributor of
   different affiliation is acceptable as long as there is no objection. Editors
   shall revisit the editorial nature of the change if there is any contention.
2. Small technical changes or additions can be discussed in GitHub issues and
   pull requests. It is the author's responsibility to ensure that interested
   parties sign off. Simply mentioning people on GitHub may go unnoticed, the
   onus remains on the author to contact interested parties and obtain their
   feedback. Closing or merging after a full week of positive review by at least
   three contributors of different affiliations is acceptable as long as there
   is no objection. Consensus will be deemed to not have been reached if
   interested parties did not sign off. At any point in time a contributor can
   request that final consensus be delayed to an in-person meeting. In this
   case, the chair puts the item on the group's agenda of upcoming
   discussions.
3. Substantial technical changes or additions are usually carried in their own
   GitHub repository by a champion. It is critical that these proposals be able
   to evolve quickly without much process. Early on in such a proposal's
   lifetime no consensus is needed and a single champion can modify the proposal
   at will. As the proposal matures it is expected that the champion will seek
   collaborators to form a small group. Gauging consensus in the small group is
   left up to the champion, with input from the chair. When a proposal is near
   maturity the champion shall bring it to an in-person meeting and seek wider
   consensus on open design points and contended issues. All decisions made by
   the small group can be revisited until consensus is reached at an in-person
   meeting.

Only 1. and 2. apply to the Working Group since the Community Group is the sole
venue where substantial work can occur. It is expected that Working Group
changes or additions in 2.'s category are validated by the Community Group
before being adopted by the Working Group. It is expected that all changes or
additions which reach consensus in the Community Group will be forwarded to the
Working Group for adoption.

## Decision process

As per the [Community Group charter](https://webassembly.github.io/cg-charter/):

    This Group will seek to make decisions where there is consensus. Groups are
    free to decide how to make decisions (e.g. Participants who have earned
    Committer status for a history of useful contributions assess consensus, or
    the Chair assesses consensus, or where consensus isn't clear there is a Call
    for Consensus [CfC] to allow multi-day online feedback for a proposed course
    of action). It is expected that participants can earn Committer status
    through a history of valuable contributions as is common in open source
    projects. After discussion and due consideration of different opinions, a
    decision should be publicly recorded (where GitHub is used as the resolution
    of an Issue).

    If substantial disagreement remains (e.g. the Group is divided) and the
    Group needs to decide an Issue in order to continue to make progress, the
    Committers will choose an alternative that had substantial support (with a
    vote of Committers if necessary). Individuals who disagree with the choice
    are strongly encouraged to take ownership of their objection by taking
    ownership of an alternative fork. This is explicitly allowed (and preferred
    to blocking progress) with a goal of letting implementation experience
    inform which spec is ultimately chosen by the Group to move ahead with.

    Any decisions reached at any meeting are tentative and should be recorded in
    a GitHub Issue for Groups that use GitHub and otherwise on the Group's
    public mail list. Any Group participant may object to a decision reached at
    an online or in-person meeting within 7 days of publication of the decision
    provided that they include clear technical reasons for their objection. The
    Chairs will facilitate discussion to try to resolve the objection according
    to the decision process.

    It is the Chairs' responsibility to ensure that the decision process is
    fair, respects the consensus of the CG, and does not unreasonably favour or
    discriminate against any Group participant or their employer.
