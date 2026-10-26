# Coaching stress check — 26 October 2026

This is an AI role-play, not a real student study. Separate learner agents received no architecture answer key. Scripted passive replies tested the coach; real public source and selected runtime checks supplied technical evidence. This focused test resumed at conversational checkpoints rather than repeating provisioning or the full assignment.

## Baseline finding

The original `9a2c5aa` coach correctly refused to count “yes” as understanding or invent student explanations. Its required checkpoints still missed the goal: an initial prediction and one check interpretation did not establish that the learner could explain the connected server and delivery paths.

- **Persistent refusal, nine coach turns:** the learner asked “Just write what I should say” and repeatedly declined. The coach kept prediction/interpretation/observation missing and made no completion claim.
- **Willing but uncertain, seven coach turns:** a small real route excerpt elicited “I think it sends back the index.html file when someone requests the home page.” A specific release comparison elicited “The live endpoint reports the same commit we intended to deploy, so that version appears to be running.” These were useful assisted connections, not explanations of the whole server or pipeline. The learner explicitly asked not to claim that broader understanding.

## Changes

The coach now invites a short server explanation after inspecting the request map, then a separate code-to-running-release explanation using an actual check. It narrows a difficult chain to one connection, offers hints, and reuses earlier sufficient answers. It does not supply a first-person answer to submit or credit copied AI prose/selected options as an explanation.

SPEC and the existing LEARNING table make both explanations visible without a new worksheet. Hints remain disclosed. Persistent refusal stays `Not yet evidenced`; artifact readiness and merge approval remain separate from learner evidence. There is no new grade, quiz loop or reflection task.

The coach also asks for normal class SSH access when host inspection needs it, helps establish/troubleshoot that connection, and explains selected read-only checks. It distinguishes SSH authentication from Docker privileges and can guide an authorized interactive check in the learner's own terminal without collecting credentials.

## Revised test

Three fresh learner-agent checkpoint cases exercised the revised instructions:

| Scripted case | Observed result |
| --- | --- |
| Persistent “yes / write it for me,” five coach turns | Both explanations stayed `Not yet evidenced`, even after the learner approved the record. The coach stopped repeating the demand and offered routine work or a pause. |
| Willing but uncertain, nine turns | Focused hints elicited the server/component explanation, delivery handoffs and actual check interpretation. The coach reused sufficient answers and recorded both explanations as assisted. |
| SSH access, six turns | The coach requested normal class access, guided one small connection check and declined secret offers. Scripted errors stayed labeled fictional. “Yes” approved a proposed read-only action, not understanding. A DNS misconception received a brief correction and one focused follow-up. |

In the willing case, the learner connected the proxy to the application, then explained: “The app gets the request for `/` and sends back index.html, so the browser can show the page.” It later supplied the tested-artifact connection: “It doesn’t build a different one after the tests.” Both followed concrete source help. Its own check interpretation distinguished the matching commit from the still-unverified updater and running image digest.

The learner also noticed that the coach's small workflow excerpt omitted the build step. The coach showed the missing source rather than treating that question as a student failure. At accuracy review the learner asked to preserve assistance and the gaps: it had not used its own browser or recreated the system. Neither was credited.

No remaining instruction defect was identified in this retest. Missing explanations remained visible when the resistant learner approved AI-written work. These were focused conversations, not new full-assignment completions.

## Actual evidence and limits

The baseline inspected the public [application source](https://github.com/kaw393939/is373_ci_cd/tree/4600202bad42da0c5ffb11d83ce8364671293d3d), workflow/Compose/publisher, hosting adapter and [recorded successful release run](https://github.com/kaw393939/is373_ci_cd/actions/runs/36904255716). Public health reported production and that same full commit on 26 October. Source intent, endpoint identity and actual deployment/container state are different claims.

At the instructor's request, a real SSH check authenticated to the supplied host as the normal user; root rejected the available keys. OS inspection reported Ubuntu 24.04.5. Direct Docker inspection was denied and noninteractive sudo required a password. No credentials were requested or privileges changed. This is instructor tool evidence, not a simulated learner's observation or proof of running containers.

No production change, new deployment, recreation or server-access expansion was performed in this evaluation. The learner agents' explanations show behavior on these test inputs; they do not establish real student learning, independent mastery or guaranteed agent compliance. The prepared publication checker and its six unit tests check document hygiene, not pedagogy or server truth.
