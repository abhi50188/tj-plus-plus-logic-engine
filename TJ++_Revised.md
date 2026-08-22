# TJ++ Revised — the argument-as-graph philosophy

## The core idea

Any argument — a paragraph, a section, a whole dissertation, an open debate
— can be represented as a graph: nodes are claims or components, and
branches are the relationships between them (support, analysis, link,
sequence). Critical thinking, in this framing, is the ability to travel the
full journey through that graph without getting stuck. Every node needs a
path in — something that supports or grounds it — and a path out — somewhere
it leads. If a node has no path in, it's an unsupported claim. If it has no
path out, it's a dead end — introduced and then abandoned. Either way, the
journey breaks there, and that's where the argument has a hole.

## Where this already lives — nothing here needs to change

This isn't a new check to bolt onto the existing process. It's the
underlying shape of what the existing process already does:

- **MEAL (Axis 12)** is this graph at paragraph scale. Main is the node (the
  claim). Evidence is a path in (support). Analysis is what actually makes
  that path real — without it, the evidence sits next to the claim but isn't
  connected to it. Link is the path out — the paragraph's claim connecting
  forward to the project's larger argument (the RQ, the conceptual
  framework, the business problem). A paragraph "fails" exactly when one of
  these paths is missing — phantom claim (no Analysis) or orphan paragraph
  (no Link) — language already in Axis 12.

- **The Handbook-anchored 12-axis rubric** is this same graph at document
  scale. The business problem is the starting node. The literature review,
  conceptual framework, methodology, and findings are the legs of the
  journey from that starting point toward the conclusion, and the conclusion
  has to lead back and close the loop on the original problem. Each axis is,
  in effect, checking that one leg of that journey is passable. The grading
  already does this — this note just names the shape underneath it.

## How to invoke it

Say "let's TJ++ this" (or "graph this out") for anything — a draft email, a
piece of feedback, an argument, a debate topic. That means: lay out the
nodes (the claims/components in play), check the branches (does each node
have support coming in and somewhere it leads going out), and flag anything
floating with no backing or introduced and then dropped. No scores, no
tiers — just "does this track end to end, or is there a gap."

## Suggested order (when running more than one layer)

If you're combining layers, run them cheapest-and-most-mechanical first,
most demanding last: node-sourcing check → non-crossing combinatorics
check → Jacobian loop check → Laplacian check → basis-shift circuit check.
Node-sourcing comes first and only once — it builds the node model
straight from the source before any of the other layers touch it. Each
step after that needs more
from the text than the one before it — the combinatorics check only needs
to know where things open and close in reading order, the loop check
needs the actual dependency direction, the Laplacian check reuses that
same matrix, and the circuit check needs the full picture of what should
be there versus what is. Running in this order means the node map gets
built once and reused, instead of re-derived at every layer, and the
circuit check goes last because it's the only one of the four that can
catch a node that's missing entirely — the other three can only comment
on what's already present, so nothing is lost by running them first.

In the rare occasion that a check turns up two mentions that might be
the same node in disguise, that's a judgment call none of the three
cheap checks can make on their own — only the circuit check's closer
read can settle it. If that happens, finish the circuit check, then
redo the non-crossing combinatorics, Jacobian, and Laplacian checks once
under the corrected node model. That's just the original order playing
out for the rest of the document, not a new procedure — and since the
circuit check never needs a second pass, the only cost is one extra
round of the cheap steps.

Run all four passes every time, even when the content looks simple at a
glance. Deciding in advance whether a check is "needed" takes about as
much work as just running it, and the whole reason this order is cheap
is that nothing here gets skipped, it gets shared.

Everything above covers the four-layer core. The full pipeline extends
past it: pairing completeness and CSF order ride alongside non-crossing
(same layer, narrower scope), and the external dependency check extends
CSF order the same way — run on request, not by default. Cross-student
convergence runs separately, once per grading cycle, not per response.
Requirement-
response runs last on every individual response, every time. Round-
count is self-triggered, situational — it only fires when the
assistant's own exchange starts circling. Minimal-basis runs once,
immediately after requirement-response — that's its real dependency,
since requirement-response is reused inside its own recursion — not
after cross-student convergence or round-count, neither of which feeds
into it or is fed by it. Oracle-splay runs once more after that — the
true final step, only after minimal-basis has already fixed the node
set, checking whether that final set's actual position in the piece
matches what an idealized version of the same argument would produce.

## Reporting the net result

The order above is about effort — building the node map once and reusing
it — not about which check gets to announce the verdict first. The result
is never any single check's finding in isolation; it's the union of all of
them. Run every layer to completion before stating any conclusion. If one
check comes back silent but another flags something, the net result is a
flag — a check's silence only means "clear" once every other check has
also run and is also silent too. Never report a check's result mid-pass as
if it settled the question; the only thing worth saying out loud is what's
left standing once the whole pass is done.

## Beyond grading: open arguments and debates

The same idea applies to a topic that doesn't have a document yet — "let's
debate mindfulness." Lay out the nodes (the facets worth arguing:
definitions, evidence for and against, mechanisms, populations, critiques)
and check whether you can travel from premise to conclusion through them
without a gap — every claim supported, every claim leading somewhere, no
facet left dangling.

## Node-sourcing check (layer zero — runs before the four-layer pass, produces the node model everything else uses)

Why this exists: none of the four layers can catch a bad node model —
non-crossing, Jacobian, and Laplacian all assume the nodes are already
right, and the circuit check only compares a finished response to whatever
basis it's handed. If the nodes are wrong at the start — two things that
should be one, or one thing that should be two — every check downstream
faithfully verifies a broken map and reports it as clean.

What it catches: nodes drawn from the phrasing of a draft in progress
instead of from the actual external source — the exact failure that let
one gradebook requirement (a discussion post plus two peer replies on two
separate days) get split into two disconnected asks, one of which then
drifted onto the wrong week entirely.

How to run it: before drafting anything, walk the actual source directly —
one rubric line, one gradebook row, one plan item — and make each one
exactly one node, whatever it contains. Don't derive nodes from the
sentences you're about to write; derive them from the source's own
structure. A source item that reads naturally as two sentences is still
one node if the source treats it as one unit (one grade, one line, one
rule). The test: would satisfying one candidate node without the other
actually count as complete, under the real standard being applied? If no,
they're one node — merge them. If yes, they're genuinely separate.

Worked example: "Week 8: Discussion — /40" is one gradebook row, so it's
one node, and that node's content is whatever the assignment actually
requires (post + two peer replies on two separate days) — not two nodes to
be independently rediscovered while drafting. Compare to "Week 8:
Discussion" and "Week 5: Discussion" — different rows, independently due,
independently graded — correctly two separate nodes.

Limits: this only works cleanly when there's a real external source to
walk (a rubric, a gradebook, a written plan). For genuinely open arguments
with no external structure, node boundaries are still a judgment call —
but the same test still applies: would one candidate node stand as
complete on its own, without the other, under whatever standard is in
play?

Cost: cheap — but "one-time" means once per check, not once for a
document's entire lifetime. Run it fresh every time on the artifact's
current text, even if node-sourcing already ran on an earlier version of
that same artifact — no memoization. Caching the old node model and
reusing it is exactly what let a rewritten paragraph slip through with a
stale node set; running fresh each time costs a little more but removes
the failure mode outright.

## Non-crossing combinatorics check (first layer, run before the others)

What it catches: claims or topics that open and close out of order — a
thread starts, a second thread starts before the first one finishes, and
they resolve out of sequence. The other three checks are blind to this
because they only look at whether a node is present, whether there's a
cycle, or whether everything's connected — none of them look at the
order nodes actually appear in the text. This check only looks at order.

How to run it: walk the piece in reading order and mark where each
recurring thread opens and where it closes. Then cancel neighboring
pairs — an open and a close sitting immediately next to each other, with
nothing unresolved between them — same as checking balanced parentheses.
Cancel one, and the tokens on either side become neighbors in turn; keep
going. If everything cancels down to nothing, the threads nest properly,
even if one sits inside another. If you get stuck with tokens left over
that never become a neighboring pair, that's the crossing — two threads
were interleaved instead of one finishing before the next began.

Worked example: a workday thread opens, then a family-time thread opens
before the workday closes (at lunch), then the workday closes, then
family-time closes (at dinner). As brackets: ( [ ) ] — nothing adjacent
cancels, so it's stuck — a real crossing. Compare to a tangent fully
wrapped inside another thread: ( [ ] ) — cancels cleanly, no crossing,
even though it reads like a detour.

Scale note: this borrows the non-crossing pairing idea from the
machinery behind the semicircle law — not the law itself. The semicircle
law needs a large ensemble of random matrices to converge to a
distribution; we don't have that and don't need it. We already know the
one actual sequence from the text, so this is a single pass with a
stack, no randomness, no ensemble, no large-n assumption.

Limits: this only catches interleaving between two threads genuinely
open at the same time. It does not catch the same topic mentioned twice
with conflicting content unless something else has already flagged
those two mentions as the same node — that's a content-identity
judgment call, not something this check makes on its own.

Nodes have to be mutually exclusive before any layer runs — no node
containing, restating, or overlapping with another. Dependencies get
added afterward, between nodes that don't already overlap; that's what
lets the matrix reduce cleanly. This is a judgment call made once, up
front — none of the four checks can make it, or catch it after the
fact, if it's wrong.

Cost: cheapest of the four checks — no matrix, no eigenvalues, just a
stack walk over the nodes in the order they appear.

## Pairing completeness check (same layer — runs before the CSF order check)

Why this exists: a destination clause can fail before order is even a
question — by naming only one CSF term when the problem needs a paired
consequence, or by naming three or more terms where one sits with no
established connection to the rest. None of the other checks catch this,
because they all assume a real, connected pairing already exists before
they run — the CSF order check in particular only judges direction once
a pair is already in place.

What it catches: an incomplete pairing — a single CSF term standing
alone, or one term in a longer list with nothing tying it to the others.

How to run it: for a destination clause naming CSF terms, confirm each
term has at least one real connection to another named term. A genuine
connection runs both directions once traced, even if unevenly — real
CSF terms sit inside the same operating system and feed back on each
other (turnover drags down productivity, and poor productivity/working
conditions also drive turnover), so a real pair is never purely
one-way. If a term comes back with no connection to anything else,
that's the flag. This check doesn't ask which direction is dominant —
that's the order check's job, run only after a pairing is confirmed.

Worked example: "...lack effective employee retention strategies to
reduce frontline healthcare employee turnover." Only one CSF term is
named — turnover — with nothing paired to it. Flag: needs a second,
connected consequence (e.g., lower labor costs) before the order check
even applies.

Limits: this only confirms a pairing exists and is connected — it says
nothing about whether the pairing is redundant (same fact under two
labels, a separate node-identity judgment made up front, not this
check's job) or about which direction is correct (the order check's
job, run next). It also doesn't require knowing the true strength of
the connection, only whether one was asserted at all — this check
never needs a real coefficient or equation, only whether a link is
present.

Cost: cheapest of all — one look per term, no matrix, no eigenvalues.

## CSF order check (same layer — runs after the pairing completeness check, alongside the non-crossing walk)

Why this exists: a destination clause can list two effects that are
genuinely connected — no cycle, nothing disconnected — and still read
backward. "Improve productivity and reduce employee turnover" and
"reduce employee turnover and improve productivity" are the same two
nodes, the same edge between them, acyclic either way, fully connected
either way. Neither the Jacobian check nor the Laplacian check can tell
these two sentences apart, because both only look at whether an edge
exists, not which way it should be read once it does. This check is
the only one of the four that looks at sentence-level word order
instead of document-level structure.

What it catches: a business-consequence (CSF) term listed before
another CSF term it's actually downstream of.

How to run it: when a destination clause names two or more CSF terms
(the same fixed categories Axis 1 already anchors on — retention,
cost, productivity, quality, compliance, revenue), walk them left to
right and check each neighboring pair with one question: does the
first one result in the second, or the second in the first? If the
written order already matches, move on. If it's reversed, flag that
pair and give the corrected order. If neither term can be said to
result in the other — no real mechanism connects them — say nothing;
don't invent a direction that isn't there.

Worked example: "...lack effective employee engagement strategies to
improve productivity and reduce employee turnover." Turnover results
in productivity loss — losing an employee creates the coverage gap and
onboarding friction that drags productivity down — not the reverse.
Written order here is productivity, then turnover: backward. Corrected:
"...to reduce employee turnover and improve productivity."

Limits: this only judges the one sentence in front of it — whether its
own left-to-right reading is internally consistent. It is not a claim
that no feedback loop exists anywhere in the real-world system (higher
costs can, in reality, eventually drive more turnover too) — that's a
fact about the wider system, not about whether this specific sentence's
forward logic holds. Checking neighboring pairs only, not every
possible pair, is sufficient at this scale: a destination clause is a
short list, not a long chain, so there's nothing a non-adjacent check
would catch that the adjacent walk misses. And the check only fires
between two CSF terms — if a listed term isn't a recognized CSF at
all, that's a different, existing failure (Axis 1's own canonical-shape
check), not this one.

Cost: cheapest of the four — no matrix, no eigenvalues, one question
per neighboring pair, riding on the same left-to-right walk the
non-crossing check already does.

## External dependency check (optional — extends CSF order check beyond the fixed vocabulary)

Why this exists: CSF order check only fires on the six fixed business
categories Axis 1 anchors on. Real-world entities outside that
vocabulary — people, technologies, science, history — get no order or
coexistence check at all, even when a well-known real-world
relationship exists between two terms sitting next to each other in
the text.

What it catches: two terms, adjacent in reading order, where the
real-world relationship between them contradicts what the text
implies — either a dependency stated backward, or two things placed
together that couldn't have coexisted in time.

How to run it: walk every neighboring pair once, in reading order —
same adjacent-only convention as CSF order and non-crossing, no
pre-filtering step before it. If both terms in a pair are CSF terms,
defer to the CSF order check and stop there — don't double-flag.
Otherwise, read the connector joining the pair, if any:
"before/after/then/first/next" — or no connector at all, since plain
adjacency defaults to this — asks the order question (does the first
term's real-world existence actually depend on the second, or the
reverse); "while/as/during/at the same time as" asks the coexistence
question instead (could the two terms' real-world time windows have
actually overlapped). Flag only when the text's claim contradicts
basic, uncontested knowledge. An ambiguous connector (a bare "and"
with no order or coexistence cue) or a genuinely debatable
relationship gets no flag, same discipline as CSF order's own limit.

Worked examples: "...the steam engine provided a new source of power.
Newton explored the meaning of gravity" — no connector, plain
adjacency defaults to the order question; steam engines depend on
prior mechanics, so the stated order is backward. "I aced my calculus
test while Newton was writing his Principia" — "while" asks the
coexistence question; a modern calculus test and the 1680s Principia
share no possible timeframe. "...to improve productivity and reduce
employee turnover" — both CSF terms, deferred to CSF order check, not
this one.

Each pair is independent — unlike the Jacobian check, no pair's answer
depends on another pair's, so there's no benefit to running this
recursively the way minimal-basis does. One pass over the adjacent
pairs is the complete check, not a partial one.

Limits: only fires on basic, uncontested real-world knowledge — not a
general fact-checker, won't touch anything genuinely disputed or
requiring specialist expertise. Not a standing check — unlike CSF
order, this needs outside knowledge per pair rather than a fixed
lookup, so it runs on request or when stakes are higher, same footing
as the basis-shift circuit check.

Cost: higher than CSF order per pair, since there's no fixed
vocabulary to check against — every non-CSF pair needs real knowledge
brought to it fresh. Pair count itself stays cheap regardless (linear,
adjacent-only, same as CSF order), and a pre-filter to cut that count
further isn't worth it at paragraph scale — deciding whether a pair is
"worth checking" costs about what checking it costs.

## Jacobian loop check (second layer, run after the non-crossing combinatorics check)

The basis-shift circuit check catches drift and omission — a node with no path
in, or no path out. It can't catch a loop: two or more nodes supporting
each other with nothing external grounding either one. A loop can pass
the circuit check cleanly, since every node in it still shows *a* path
in — that path just happens to be the other node in the loop, which a
per-node check can't see.

Run this on every pass, not just ones that look branching at a glance. A
truly straight-line reply (post → citation → citation → citation →
nudge → question) can't loop by construction — but whether a piece is
truly straight-line isn't always obvious from a first read, and
rambling or unusually organized student work can bury a cross-reference
that only shows up once you actually trace the dependencies. Since the
crossing check, this check, and the Laplacian check now run as one
combined pass, skipping ahead of time based on appearance doesn't save
meaningful effort — the node map gets built regardless — and it risks
missing the one case this check exists to catch.

How to run it: write one line per node for what it actually depends
on — that's the node's equation. The Jacobian is the partial derivative
of each node's equation with respect to every other node. A clean graph
reduces the way you'd solve it by hand — figure out the first node, plug
it into the next, and so on until nothing's left. A loop is the spot
where that breaks down: two or more nodes that can't be solved in any
order because each one needs the other first. That's what to flag — not
"instability," just an unresolved knot.

Quick tell, before building the full matrix: scan for a mirrored
pair — node A depends on B, and B depends on A, with nothing else in
between. That pair always has a negative determinant on its own (the
diagonal is zero, the off-diagonal entries multiply to a positive
number, so the determinant comes out negative) — that's the giveaway, no
eigenvalue solve needed. If you do run the full matrix, a genuine loop
like that produces a plus/minus eigenvalue pair.

Longer loops (three or more nodes in the ring) don't show up as a
mirrored pair, and the two-node scan above won't catch them — the tell
is different at that length. A three-node loop produces one real
eigenvalue plus a complex-conjugate pair; a four-node loop produces a
real plus/minus pair plus a complex-conjugate pair on top; and it keeps
splitting that way as the ring gets longer. The plus/minus real pair
above is what the shortest possible loop looks like, not the general
case — the rule that holds at every loop length is that *any* nonzero
eigenvalue, real or complex, means a loop exists somewhere. A genuine
acyclic dependency chain reduces to a strictly triangular matrix once
ordered, which is always nilpotent, so every eigenvalue comes out
exactly zero — never complex, never nonzero. Complex eigenvalues
showing up at all is therefore an unambiguous tell on its own: the only
way to get them is a loop of three nodes or more.

Note: this is a different "eigen" than the shift-vector eigen used in
the basis-shift circuit check. That one is a magnitude of drift on a single
node. This one comes from an actual matrix built from real traced
dependencies between nodes — different tool, different failure mode
(loops, not drift).

Scale note: this is a small, deterministic matrix built from specific
traced dependencies, not a random one — statistical results about large
random matrices (e.g., the semicircle law) don't apply here and aren't
worth reaching for, regardless of how lattice-like a graph looks. The
determinant/eigenvalue check above is the right tool at this scale.

Cost: nearly free. The row/column scan for drift and omission is already
part of the ordinary TJ++ pass; adding "does anything loop back on
itself" is one more scan, not a retry loop or extra drafting cost.

## Laplacian check (third layer, built from the same J as the loop check)

1. **Start with J** — the Jacobian already built for the loop check,
   direction intact (J[i][j] = 1 means i depends on j).
2. **Symmetrize J into A** — A[i][j] = 1 if J[i][j] = 1 or J[j][i] = 1
   (either direction counts), 0 otherwise. Direction is gone at this
   step. Note: if a pair already had dependencies running both ways (a
   loop, like Bread/Toast), A comes out identical to J and this step
   changes nothing visibly. If a pair only had one direction (a plain
   dependency, no loop), A picks up a second 1 that J didn't have —
   that's the real transformation happening.
3. **Build D, the degree matrix** — a diagonal matrix where D[i][i] =
   the row-sum of A for node i (how many connections it has). Every
   off-diagonal entry of D is 0.
4. **Subtract: L = D − A.**
5. **Take the eigenvalues of L and count the zeros.** One zero = one
   connected piece, everything's whole. Every zero beyond the first is
   a piece that split off entirely — no connection reaches it, so
   there's nothing there to disagree across, hence the flat zero.

What it catches that the other two layers don't: something locally
coherent — supported, leading somewhere, no circular dependency inside
it — but with no connection to the rest of the argument at all. Filler,
a redundant tangent, or unchecked AI-generated padding usually looks
exactly like this: smooth on its own, disconnected from everything
else.

Run it recursively, not just once: a single pass only catches a full
disconnect. Something attached by a single thin edge is still
functionally separate, and that won't add a zero — it shows up as a
small but nonzero second-smallest eigenvalue instead. When a piece's
second-smallest eigenvalue is notably small, split it at the seam its
eigenvector points to, then repeat steps 2–5 on each half. Stop when
nothing splits further.

Cost: cheap — step 1 is already done for the loop check, so this only
adds steps 2–5 on top.

## Basis-shift circuit check (fourth layer — run last when combining with the others; still fine to run standalone for a quick single-pass review)

When you want to verify a reply or draft hasn't drifted from its source, run the circuit check:

1. **Read the context** — the question, rubric, or expectations doc. This is the basis.
2. **Build the basis vector** — identify the nodes that SHOULD be in the reply. Each node is set to 1 (circuit live).
3. **Build the reply nodes** — what the reply actually contains.
4. **Compute the shift** — basis minus reply. Each node is binary: 1 (anchored, current flows) or 0 (open circuit).
5. **Read the shift vector** — any −1 is an open circuit. Two kinds:
   - Node in basis but missing from reply → **omission**
   - Node in reply but not in basis → **drift**

Nodes are dynamic — derived from the context each time, never fixed upfront. The basis is always the source document or question. The shift vector points exactly to the problem dimension without a full re-read.

**A basis doesn't have to be written down.** "No formal prompt, rubric, or document" is not the same as "no basis" — it's a narrow inference that skips the check instead of running it. A basis can be an implicit schema: the generic, unwritten shape of what a complete answer looks like, independent of the one instance in front of you. "Steps to get dressed" below has no author and no written question — the basis is just the ordinary shape of the task. The same holds for something like "recount your day," which has an implicit schema too (a meal count, work, family logistics) even with zero formal prompt behind it. Before concluding a check doesn't apply for lack of a source, check for an implicit schema first — that's usually where the real basis was hiding.

**Example — "What did you eat for breakfast?"**
- Basis: [breakfast items: 1]
- Reply: eggs ✓, toast ✓, dinner plans ✗
- Shift: [eggs: 0, toast: 0, dinner plans: −1] → dinner plans is the open circuit (drift)

**Example — "Steps to get dressed"**
- Basis: [underwear: 1, socks: 1, pants: 1, shirt: 1, shoes: 1]
- Reply: shirt ✓, pants ✓, shoes ✓, brush teeth ✗ (drift), underwear missing (omission), socks missing (omission)
- Shift: [underwear: −1, socks: −1, shirt: 0, pants: 0, shoes: 0, brush teeth: −1] → three open circuits

Use this when something feels off or stakes are higher. TJ++ alone covers most cases — the circuit check is the optional verification layer on top.

**Eigenvalue vocabulary** — the shift vector's components are the eigenvalues for each node. A component at zero means the node is anchored — small eigen, circuit closed. A large negative component means significant drift or omission — large eigen, circuit open. The overall magnitude of the shift vector tells you how far the output has drifted from the basis as a whole. When invoking TJ++, you can use either vocabulary — "open circuit on node X" or "large eigen on node X" — they point to the same thing.

**Standing checks — run every time, regardless of context.** The basis vector itself is dynamic: which nodes matter is derived fresh from the context each run, never fixed upfront. But two checks are properties of the circuit-check mechanism itself, not of any particular context, so they apply on every single pass, for every node, with no exception and no judgment call about whether they're needed this time:

- **Example nodes** — every content node should carry an example node alongside it. The form the example takes depends on the context: if the basis includes a document, the example is the relevant section of that document; if not, it is a concrete illustration. A content node with no example alongside it is an open circuit — the eigen will be high and the shift vector will catch it.
- **Plain language** — say it in the fewest words that land. If a sentence needs unpacking to understand, it is an open circuit — regardless of how well-anchored the node otherwise is. A node can be fully supported (example present, citation correct, argument sound) and still register as an open circuit on this check alone if the phrasing makes the reader work to parse it (e.g., compound-noun stacks like "anchor building blocks" instead of "building blocks"). **One job per sentence** is the sentence-level instance of this same check: a citation sentence that both states the finding and bridges it to the specific example in one breath — usually signaled by a trailing "which," "a dynamic that," or "a pattern that" clause — is doing two jobs at once and should split into two sentences, one job each (state the finding, then a short sentence bridging it to the example). This is not new length overhead; it is the same total content, just not stacked in one clause. The Zachary voice anchor already does this (see Example_Para.docx: "Hunt et al. (2018) documented... These outcomes suggest...").

These two are checked on every TJ++ or basis-shift pass by default — not something to remember to add when a draft "feels off." Treat them the same as reading the basis document itself: a required step, not an optional add-on.

**Cost:** moderate — building the basis vector means reading the full context once, but the shift itself is just a set diff after that. Reusing node-sourcing's model where one already exists avoids a second full read.

## Eigen-revealed walls (BEF discussion gate)

A wall caught during Step 3 of the Disc Spin mechanism (the original Fit/draft
attempt) is handled as always — greedy, drop it, move on, no discussion
needed. That mechanism is unchanged.

A different case: a citation survives Step 3, gets drafted in, and only the
TJ++ or basis-shift circuit check reveals it doesn't actually hold up
(topical misfit, or fails a standing check badly enough to be
unsalvageable). Call this an **eigen-revealed wall**. When this happens —
regardless of how many citations remain afterward, even if 1 or 2 survive,
not just at 0 — it opens a **discussion gate**: does adding BEF as a
strengthening citation genuinely add weight to this specific reply, or not?
This is never automatic. BEF only gets added if the discussion concludes
it's actually load-bearing for the argument — same hard-gate discipline as
the review-before-commit rule, one layer deeper.

Scope: this applies to the slow, one-at-a-time, eigen-reviewed workflow
(small batches, full TJ++ pass per student) — not the fast batch-processing
default the Disc README's Spin mechanism is built for. The original "no
swap-in bridges, BEF reserved for 3-wall only" restriction exists to
protect batch-speed and corpus-diversity at scale; those costs don't bind
the same way when every draft already gets this much scrutiny. In fast
batch mode, the original rule stands unchanged.

## Cross-student convergence check (separate pass — runs once per grading cycle, across the cohort, reuses the Laplacian layer only)

**Generalization note:** "student" is the object this check was first
written for, not a hard requirement — the same move applies to any set of
comparable instances sharing a template (documents, submissions, mirrored
reference files), as long as corresponding node positions can be
identified across them. Read "student" as "instance." Don't reinvent this
check under a new name just because the object changed.

The four layers above check whether one student's argument holds together.
This one checks whether two students have converged on the same territory —
the originality-risk question, not the coherence question. Applies once per
cycle after some or all students have a state entry, not during any
individual student's own TJ++ pass.

**Trigger: ask, don't self-initiate.** Unlike the other standing checks in
this document, this one doesn't fire on its own. The reason to run it isn't
fixed to one context — it could be a grading pass, or it could just be a
hunch that two students' posts sound alike — but either way, that reason has
to come from outside the check itself; nothing about a single student's
entry says "go compare this to the cohort." Ask first ("want me to run the
cross-student convergence check on the cohort so far?") and only run it once
the answer is yes. This is the one exception to the rest of this document's
"run it without being asked" discipline, because the need for it is
genuinely situational — it depends on why you're looking, not on anything
detectable in the draft in front of you the way the other checks can be.

**Why Laplacian only, not Jacobian:** Jacobian needs real dependency — one
claim needing another to resolve. No such relationship exists between
independent students; neither one's problem needs the other's to make sense.
Laplacian only ever needed an undirected match relationship, so it's built
directly from "these two students match," skipping Jacobian entirely.

**Which nodes:** population and the CSF pair from the business problem.
Nothing else. Framework is ruled out — popular theories (Transformational
Leadership, Kotter, etc.) get reused across unrelated topics constantly, so
a framework match carries no signal. Research question is ruled out too —
it's structurally just population and CSF restated inside the required
template sentence, so checking it again double-counts instead of adding
anything.

**How to run it:** each student is a plane; population and CSF sit at fixed
positions on every plane since the template is shared. Build two separate
match-graphs, one per node: for each pair of students, mark a match (0) or
no match (−1) on population, and separately on CSF pair. Every student gets
checked against every other student directly — not sequentially, not
against one fixed reference — so the result doesn't depend on roster order.

**Reading it:** run Laplacian on each graph separately. A block that's
mostly −1 is healthy — spread out, low convergence. Students landing in the
same connected piece on the CSF graph is a signal on its own; landing
together on the population graph too, in the same pass, is a stronger one —
that's the AND combination, the real flag. Report all three: population-only
matches, CSF-only matches, and the AND-combined flag. Combined is what's
worth a mentor's attention; either column alone is lower confidence but
still worth surfacing as context.

**Cost:** cheap — both fields are categorical, no decimals or word-overlap
scoring needed, just match or not.

## Requirement-response check (final step — every response, every time, run last)

Same two-plane framing as the cross-student convergence check above, just at
cohort size two instead of N: the source — a question, a rubric, an email,
or an implicit schema (the generic, unwritten shape of a complete answer,
even with no formal prompt behind it — see the note on this under the
basis-shift circuit check) — is one plane, the response is the other. The
check is asymmetric here, not symmetric: a match is the goal, not the risk.
The source sets the requirement; the response is being checked against it,
not compared to it as a peer. Don't conclude this check doesn't apply just
because there's no written source in front of you — check for an implicit
schema first. A free-standing narrative like "recount your day" still has
one (meals, work, family logistics).

**How to run it:** build the basis set from the source — every point that
needs an answer. Build the reply set from the response — every point
actually addressed. Commons (on both planes) are addressed, done. Missing
(on the source's plane only) is a real candidate gap. Excess (on the
response's plane only) is added content, worth a look but not automatically
wrong.

**Reuse the basis from node-sourcing, don't redo it.** The basis set here
is the same one the node-sourcing check already built directly from the
source before drafting started — it doesn't need rebuilding, since redoing
correct work just spends effort without changing the answer. Only the
reply set needs building fresh here, since that's the thing that changed
between the start of the task and now. If node-sourcing was skipped for
this task, build the basis from the source directly at this step instead —
same test, just late.

**Apply judgment to what surfaces, don't just report the raw diff.** A
missing item can be a legitimate skip — a contingency that never triggered,
an FYI that doesn't need acknowledgment, something already covered
elsewhere. An excess item can be legitimate, useful context volunteered on
top of what was asked. Decide each one before reporting; only the real gaps
and the real drift are worth surfacing, same net-result discipline as the
rest of TJ++.

**Where this sits:** run it last, after the four-layer pass and after
that cycle's cross-student convergence pass (if one has already run),
on every response, every time — not
optional, not something to skip because a draft looks complete. Everything
before this step checks whether the response holds together on its own
terms. This is the one step that looks back out at the actual source to
confirm nothing got missed and nothing got added that doesn't belong.

**Cost:** cheap — reuses the same commons/missing/excess logic already
built for the basis-shift circuit check, just positioned as the closing
move instead of a mid-pass layer.

## Round-count check (self-referential — flags drift in the assistant's own exchange, not the work being reviewed)

Why this exists: every other check in this document runs on a finished draft or a source document. This one runs on the assistant's own back-and-forth, because the same redundant-node and reopened-thread failures that show up in student work can just as easily show up in how the assistant is responding — and nothing else in this document is positioned to catch that, since it all assumes the object being checked is someone else's writing.

What it catches: the assistant re-answering the same underlying question multiple times, each time defending a narrower technical point than the one actually being asked, while believing each round is progress. The tell is round count, not content — if the same topic is still open after about three exchanges, the issue usually isn't that the answer is wrong, it's that the closes aren't landing on the real thread.

Trigger: more than ~3 rounds of back-and-forth on one point within a single topic, or noticing the same hedge repeating ("not this, not that") without the thread actually resolving. This is meant to be self-initiated — the assistant notices the round count and says so ("we seem to be circling on this, want to run the check?") rather than waiting to be sent back to it, the same way every other standing check in this document runs without being asked.

How to run it: pause and treat the assistant's own last several turns as the document. Build the node model of what was actually asked (one question, usually), then run non-crossing (did the thread close and reopen more than once?) and requirement-response (did the reply deliver more than the question asked for?) against it. A thread that reopened repeatedly, or answers that grew more elaborate than the question warranted, is the flag.

Worked example: a Wk9 exchange over whether a population/outcome pair formed a Jacobian loop. The substantive answer (no cycle) was correct after the first pass; four more rounds followed re-litigating matrix construction details the question never asked about — round count alone would have flagged this before content review was needed.

Limits: this check flags that an exchange has stopped converging — it doesn't determine who was right. Use it to trigger a stop-and-recheck, not as a verdict. Round count alone can't distinguish a reopened thread from a long but genuinely-converging exchange, so use a concrete test rather than the count by itself: did this round change the actual conclusion, or only the wording defending the same conclusion already given? If the answer at round four is the same as the answer at round one and only the justification changed, that's a reopened thread. If the answer itself changed — a new fact surfaced, an assumption got corrected, a prior claim turned out wrong — that's real convergence, and the round count was just the cost of getting there, the same way a legitimately long node-identity call elsewhere in this document isn't a failure just because it took several passes.

Cost: cheap when it fires, and it rarely fires — reuses non-crossing and requirement-response wholesale instead of building new machinery, and the self-trigger means it only runs on exchanges long enough to actually need it.

## Minimal-basis check (recursive — run last, after every other applicable check has passed)

Why this exists: every check above confirms an argument is valid — sourced (node-sourcing), correctly ordered (non-crossing), acyclic (Jacobian), connected (Laplacian), matching its source (basis-shift), answering what was asked (requirement-response). None of them confirm the argument is minimal. A node can pass every one of those checks individually — properly sourced, in order, no cycle, connected, on-basis — and still be dead weight the argument doesn't need, restating a point already made elsewhere in different words. That's the gap this check closes: not "is this valid" but "does every remaining node still earn its place."

What it catches: redundant nodes that survive every other check clean, one at a time, because those checks were never built to compare a node against the rest of the draft — only against the source or against internal consistency. The Ashley draft earlier in this session is the reference case: the same "population can act, the individual's choice can't" reasoning stated in the opening sentence, again in the "answers the question" sentence, and again in the closing nudge — each instance individually sourced, ordered, acyclic, and on-basis, so nothing upstream flagged it. Only comparing each instance against what remained caught it.

Trigger: run once, immediately after requirement-response confirms the full draft satisfies what was asked. That's the one hard dependency — requirement-response gets reused as one of the two recursion tools below, so it has to have already passed once on the uncut draft before any node gets tested for removal, or there's no confirmed baseline to protect against cutting something that was quietly covering a real gap. It does not need to wait on cross-student convergence (a separate pass over the source material, not the reply) or round-count (self-referential to the assistant's own exchange) — neither one touches the reply's node set, so it makes no difference whether either has run yet. This is a closing pass on the response itself, not a substitute for any of the above — it assumes the draft already passes requirement-response and only asks whether it's also minimal.

How to run it: take the checked draft's node list. For each node in turn, propose cutting it, then rerun two checks already in this document against the reduced draft — Laplacian (does removing this node disconnect the argument, meaning it was actually a bridge, not filler) and requirement-response (does the reduced draft still fully satisfy what was asked). If both still pass with the node gone, the cut sticks — that node was genuine dead weight. If either fails, restore the node and move to the next candidate. Once a full pass is complete, repeat it on the reduced draft — cutting one node can reveal a second one is now also droppable, or can turn a previously-safe node into a now-necessary bridge, so a single pass isn't sufficient. Stop when one full pass produces zero cuts — that's the fixed point, and what's left is the minimal set.

Worked example: the Nykia CITI-boundary email, run clause by clause. One candidate looked like a likely cut on sight — "it has to be self-directed" sits right next to the boundary statement it seems to restate. Cutting it failed the Laplacian test: without it, "the same as everyone else, who downloaded their term plan..." has nothing to attach to — the clause was the bridge connecting the boundary to the fairness point, not a restatement of either. Every other clause failed requirement-response on removal (each was explicit required content). Full pass, zero cuts, fixed point on the first try — confirmation that the manual trimming done across earlier rounds had already found the minimal draft, not a failure of this check to find anything.

In butchery terms: every other check confirms the animal is sound. This is the pass that keeps cutting until no more dead weight comes off — what's left on the block at that point are the succulent bits: connective tissue and load-bearing muscle, not the trim.

Limits: this doesn't replace the checks it reuses, it reruns them — so it inherits their limits too (Laplacian's "does this need a further split" judgment call, requirement-response's "is this excess actually legitimate" judgment call). It can't run before the other checks pass, since a node that looks redundant in an unfinished draft may just be waiting on a dependency that hasn't been added yet. And a fixed point reached on the very first pass isn't a sign the check found nothing to do — a draft that's already been trimmed across several manual rounds should converge immediately; that's the expected result, not a miss.

Cost: scales with node count and how many passes it takes to reach the fixed point, but each cut-test reuses Laplacian and requirement-response rather than new machinery, and an already-trimmed draft converges in one pass — so the typical cost is low even though the mechanism itself is recursive.

## Oracle-splay check (final layer — runs last, after every other check, including minimal-basis)

Why this exists: every check above confirms the argument is valid — sourced, ordered, acyclic, connected, on-basis, minimal. None of them confirm it was actually built as one coherent piece. A graph can pass every one of those checks and still have a node sitting in the wrong place — either abandoned after being introduced, or occupying a slot the argument's own shape never provided for. Structural validity and structural soundness aren't the same thing, and nothing above this layer can tell them apart.

What it catches: a node that ends up positioned differently than an idealized version of the same argument would place it — either a node that gets touched once and never reintegrated where the shape of the piece calls for a return, or a node that has no natural home in the expected pattern for this kind of writing at all.

How to run it:
1. Take the final node set, after every other check has already run and minimal-basis has already cut whatever it was going to cut. This check never adds or removes a node — same set both trees.
2. Build the actual tree: walk the real reading order and simulate splay operations — first mention of a node is an insert, any later return to that same node is an access, which splays it back to the root. The resulting shape reflects what the piece actually did. Splay, not a balanced tree like red-black — a red-black tree stays indifferent to access frequency by design, which would erase the exact signal this check needs. Splay pulls a repeatedly-touched node toward the root precisely because it was touched again, which is what lets a hub surface on its own.
3. Build the Oracle's tree from the same nodes, treating each spoke as an anonymous position — Author 1, Author 2, Author 3 — never by what any citation specifically argues. Using the established pattern for this kind of writing — an explicit schema where one exists (a day-recap's meals/work/family-logistics buckets), or the pattern already demonstrated by clean examples of the same genre (a mentor reply's hub, touched again after every spoke, with the close echoing whichever spoke was touched last) — place each node where that pattern says it belongs, based on role and position only.
4. Take the shift: compare the two trees node by node.
5. Read it: a sound piece comes back sparse, close to flat. Any real, concentrated mass in the shift points at exactly the node that drifted, and where.

Worked examples: four of five mentor replies close by echoing whichever citation was touched last — matches the Oracle, flat shift. One doesn't — its last-touched node never gets echoed again, and the close reaches back to two earlier ones instead — shift concentrates entirely on the orphaned node. Separately, "I ate breakfast, it was good, my work was bad, and I lost money on shares" — breakfast and work land inside the established meals/work schema cleanly; shares has no bucket in that schema at all, and the shift concentrates there.

Limits: needs a real Oracle to compare against, and building one is a judgment call, same footing as basis-shift's own basis or external dependency's real-world knowledge — this check can't bootstrap that from nothing. It needs a light touch of content to work at all — recognizing which earlier node a later line is about requires reading enough to place it. What it stays blind to is whether that content is any good — a citation-bridge can be a total stretch and still land in exactly the position the Oracle expects, because this check only ever asks where, never whether. Only meaningful on the already-pruned final graph — run any earlier and it just re-detects problems the prior layers exist to catch.

Cost: cheap at the scale this runs at — a hand-trace over a handful of nodes, no real data structure needed. The only real cost is constructing the Oracle, which is upfront judgment, not ongoing computation.
