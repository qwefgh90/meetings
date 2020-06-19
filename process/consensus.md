# 합의 절차 (Determining consensus)

합의는 기준을 세우는데(standars process) 매우 중요한 부분이다:

* 합의를 하는 것은 각 전문가들이 자신감을 갖고 제안 추진 할 수 있도록 도와준다.
* 합의는 이미 다뤘던 주제를 다시 다루는 것을 막아준다. (단, 다시 토론해야 될 정도로 변경이나 새로운 정보가 많지 않을때)
* 구성원들이 자신의 발언이 잘 전달되지 않는다고 생각하면
  모든 일과 절차가 의미가 없어질 수 있다. 그래서 찬반을 기록하는 것은 합의하는
  과정에서 매우 중요한 일이다.

## 대면 회의에서의 합의 (In-person meeting consensus)

각 전문가들은 합의를 하기 위한 합의점들을 제시해야하며 
토론 과정에서 새로운 합의점들이 추가될 수 있다. 

합의 투표는 의장에 의해 진행한다:

1. 전문가는 모두가 볼 수 있게 기록되어 있는 질문을 한다.
   합의점과 관련된 많은 것들이 순서대로 투표로 붙여질 것이며, 
   무엇을 투표할지 투표하기 전에 모두에게 전달되어야 한다.
2. 의장은 순서대로 참석자들에게 질문에 대한 의견을 듣고 찬반을 여부를 묻는다.
   참석자는 거수를 통해 완전 찬성, 찬성, 중립, 반대, 완전 반대, 기권 중 하나를 선택할 수 있다.
   서기는 투표 결과를 기록한다.
3. 필요한 경우 의장은 특정 참석자들에게 하고싶은 말이 있는지 물을 수 있다. (이는 서기를 위한 과정 일 수 있음)
4. 의장은 합의가 되었는지 되지 않았는지 결정할 수 있다.
5. 참석자는 결정에 대한 반대 의사를 표명할 수 있다. 
   반대한 사람은 기술적으로 반대하는 이유를 설명해야하며 새로운 제안을 해야한다.
   이러한 제안은 모호하거나 불완전할 수 있다. 주의사항: 워킹 그룹에서 
   공식적인 반대는 W3C Director에 의해 검토된다. (커뮤니티 그룹 제외)
   반대하는 이유나 관련된 이론적 해석을 제시하지 않을 경우
   검토 대상에서 제외될 수 있다.

합의를 위해 필요한 찬성표의 수는 정해져 있지 않다. 경우에 따라 한명의 개발자 또는 사용자에 의해 
합의가 되지 않을 수 있다. 중요한 점은 모든 참석자는 합의 절차가 잘 동작한다고 믿는 것이다.
의장은 합의위에서 새로운 합의를 할 수 있도록 노력해야한다.

합의가 되지 않은 건을 다시 회의에 올리고 싶다면 보다 많은 정보가 제시해야 할 것이다.

누가봐도 간단한 주제에 대해서는 빠른 합의 또는 만장일치를 위해 이의제기 요청이 있는지 
가볍게 묻고 넘어갈 수 있다. 합의를 빠르게 진행하기 위해서는 하나의 반대만 
들어봐도 충분하다. (A single objection is sufficient 
to force the above consensus process.)

## 온라인 상에서의 합의 절차 (Online consensus)

회의(in-person meetings)를 통해 많은 업무가 진척될 수 있다. 설계를 한다던지 새로운 아이디어를 어느 수준까지 구체화 시킬 수 있다.
끝에는 Github 저장소나 화상 회의를 통해 합의에 도달할 수 있다.
화상 회의에서 결정된 내용은 모두 기록되며 대면 회의와 같은 방식으로 공개될 것이다.

다음은 온라인상으로 의사 결정하는 것과 관련된 개념이다.

* 다른 소속의 기여자(Contributors)들이라 함은 다른 기관이나 다른 회사에 연관된 개인을 의미한다.
* 관심있는 집단(Interested parties)은 WebAssembly 커뮤니티에 참석하면서 특정 주제에 관심있는 개인들, 회사들, 기관들이다.
* 작은 집단(Small group)은 특정 제안에 관심있는 커뮤니티 그룹나 워킹 그룹 구성원들이다.

다음 케이스들은 구별된다.

1. 편집자(Editor)는 독자적으로 기술과 관련없는 변경을 할 수 있다. Github 이슈나 Pull Request로 충분하다.
   Their title should identify them as editorial. 반대가 없는한 최소 하루 이상 다른 기관의 사람에 의해 검토를 받고 이슈를 닫거나 병합할 수 있다.
   Editors shall revisit the editorial nature of the change if there is any contention.
2. 작은 기술적 변경사항이나 기능 추가등은 Github 이슈나 Pull Request로 관리될 수 있다. 
   작성자는 책임지고 관심있는 부서들이 승인을 하도록 만들어야 한다.
   간단하게 Github에 사람을 호출하는 것은 눈에띄지 않을 수 있다. 작성자는 책임지고 지속적으로 관심있는 집단과 연락하고 피드백을 받아야 한다.
   반대가 없는한 최소 일주일 이상 검토를 받은 뒤 이슈를 닫거나 병합할 수 있다.
   만약에 관심있는 집단이 승인을 하지 않는다면 합의에 도달하지 않는 것으로 여겨진다.
   기여자(contributor)는 다음 회의로 합의를 미루고 의장은 다음 회의의 안건으로 올릴 것이다.
3. 큰 기술적 변경사항이나 기능 추가등은 전문가에 의해 별도 저장소에서 다뤄진다. 이러한 제안들은 많은 절차 없이 빠르게 진척되어야 한다.
   이른 시점에 합의가 필요하지 않으며 전문가는 스스로 제안을 수정할 수 있다. 제안이 어느정도 성숙되면 의장은 작은 그룹을 만들기 위해 구성원을 찾을 것이다.
   작은 그룹에서 합의를 진행할지는 전문가에게 달려있다. 제안이 많이 성숙해지만 대면 회의에 제안을 소개하고 설계와 여러가지 쟁점에 대한 합의을 진행할 것이다.
   작은 그룹에 의해 내려진 결정은 대면 회의까지 계속 참조될 수 있다.

보통 커뮤니티 그룹은 할일이 많은 그룹이기 때문에 1번과 2번은 케이스에 해당되지 않는다. 1번과 2번은 워킹 그룹에만 적용된다.
It is expected that Working Group
changes or additions in 2.'s category are validated by the Community Group
before being adopted by the Working Group. 커뮤니티에서 발생한 모든 합의는 워킹 그룹에 전달되어 채택될 수 있다.

## 결정 절차 (Decision process)

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
