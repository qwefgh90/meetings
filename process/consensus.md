
# 컨센서스 결정(합의)

컨센서스는 표준을 결정하는 프로세스에서 매우 중요한 부분이다.

* 컨센서스를 형성하는 것은 각 전문가들이 더욱 자신있게 제안 할 수 있도록 도와준다.
* 컨센서스는 불필요하게 했던 토론을 다시 하는 것을 막아준다. (단, 다시 토론해야 될정도로 변경이 많지 않을때)
* 만약 구성원이 자신의 목소리가 잘 전달이 안된다고 생각하기 시작하면 표준을 만드는 작업 그대로 멈출 수 있으므로 
  찬반에 대해 기록하는 것 역시 컨센서스를 만드는데에 매우 중요한 작업이다.

## 대면 회의 합의 절차

대면 회의를 할때 각 전문가들은 합의점을 제시해야하며 토론 과정에서 새로운 합의점들이 추가될 수 있다. 

합의 절차는 다음과 같다:

1. 전문가는 모두가 눈으로 직접 읽을 수 있는 형식으로 질문을 한다. 
   모든 합의점이 제시된 이후 이를 투표에 붙일 수 있다.
2. 의장은 순서대로 모든 참석자에게 질문에 대한 의견을 듣고 각 참석자 순서대로 찬반을 여부를 듣는다.
   참석자는 거수를 통해 완전 찬성, 찬성, 중립, 반대, 완전 반대, 기권 중 하나를 선택할 수 있다.
   서기는 투표 결과를 기록한다.
3. 필요한 경우 의장은 특정 참석자들에게 투표한 이유에 대해 말하고 싶은지 물을 수 있다. (이는 서기를 위해서 하는 과정 일 수 있음)
4. 의장은 합의가 되었는지 결정할 수 있다.
5. 참석자는 결정에 대한 반대 의사를 표명할 수 있다. 
   반대한 사람은 기술적으로 반대하는 이유를 설명해야하며 새로운 제안을 해야한다.
   이러한 제안은 모호하거나 불완전할 수 있다. 주의사항: 워킹 그룹에서 
   공식적인 반대는 W3C Director에 의해 검토된다. (커뮤니티 그룹 제외)
   반대하는 이유나 이론적 해석을 제시하지 않을 경우 검토 대상에서 제외될 수 있다.

합의를 위해 필요한 찬성표의 수는 정해져 있지 않다. 경우에 따라 한명의 개발자 또는 사용자에 의해 
합의가 되지 않을 수 있다. 중요한 점은 모든 참석자는 합의 절차가 잘 동작한다고 믿는 것이다.
의장은 합의위에서 새로운 합의를 할 수 있도록 노력해야한다.

합의되지 않은 건을 다시 토론하고 싶다면 반드시 더 많은 정보를 제시해야 할 것이다.

누가봐도 간단한 주제에 대해서는 이의제기 요청을 간단히 받고 넘어갈 수 있다.
빠른 합의를 위해 하나의 반대만 들어봐도 충분하다.

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
