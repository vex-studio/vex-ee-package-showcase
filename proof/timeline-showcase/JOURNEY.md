# Timeline Showcase Journey Ledger

Updated: 2026-07-14T23:09:10.058112+00:00
Inventory: **82** TrackClipType rows · **82** with ≥1 playable sample.

## Shared stage primitives

| Primitive | Role |
|-----------|------|
| Playable Director + Timeline asset | Author tracks/clips |
| SubScene actor (Transform / PhysicsBody / Targets) | Binding target |
| EntityLinks map (where needed) | Resolve schema links |
| StatAuthoring (time/essence/ui) | Stat-driven clips |
| Host Main Scene cube | MMI baseline proof |
| Package Sample~ / Showcase builders | Canonical demos (Vex/Showcase/Build *) |

## Package queue (easy → hard)

- **com.bovinelabs.timeline.transform**: 7 clips · 7 sampled · status=sample-mapped
- **com.bovinelabs.timeline.parenting**: 1 clips · 1 sampled · status=sample-mapped
- **com.bovinelabs.timeline.entitylinks**: 4 clips · 4 sampled · status=sample-mapped
- **com.bovinelabs.timeline**: 2 clips · 2 sampled · status=sample-mapped
- **com.bovinelabs.timeline.audio**: 1 clips · 1 sampled · status=sample-mapped
- **com.bovinelabs.timeline.distance**: 1 clips · 1 sampled · status=sample-mapped
- **com.bovinelabs.timeline.essence**: 4 clips · 4 sampled · status=sample-mapped
- **com.bovinelabs.timeline.grid.influence**: 4 clips · 4 sampled · status=sample-mapped
- **com.bovinelabs.timeline.particles**: 1 clips · 1 sampled · status=sample-mapped
- **com.bovinelabs.timeline.physics**: 38 clips · 38 sampled · status=sample-mapped
- **com.bovinelabs.timeline.playerinputs**: 9 clips · 9 sampled · status=sample-mapped
- **com.bovinelabs.timeline.time**: 3 clips · 3 sampled · status=sample-mapped
- **com.bovinelabs.timeline.ui**: 7 clips · 7 sampled · status=sample-mapped

## Full checklist

### com.bovinelabs.timeline.transform

| Track | Clip | Bind | Soft-gates | Sample | Status | Learned |
|-------|------|------|------------|--------|--------|---------|
| `TransformRotationTrack` | `RotationLookAtTargetClip` | `UnityEngine` | — | `com.bovinelabs.timeline.transform/Sample~/Transform Showcase/Timelines/Rotation_0.playable (+2)` | `sample-mapped` |  |
| `TransformRotationTrack` | `RotationLookAtStartClip` | `UnityEngine` | — | `com.bovinelabs.timeline.transform/Sample~/Transform Showcase/Timelines/Rotation_1.playable` | `sample-mapped` |  |
| `TransformScaleTrack` | `ScaleStartClip` | `UnityEngine` | — | `com.bovinelabs.timeline.transform/Sample~/Transform Showcase/Timelines/Scale_3.playable` | `sample-mapped` |  |
| `TransformScaleTrack` | `ScaleClip` | `UnityEngine` | — | `com.bovinelabs.timeline.time/Sample~/SlowMo Demo/SlowMoTimeline.playable (+2)` | `sample-mapped` |  |
| `TransformPositionTrack` | `PositionStartClip` | `UnityEngine` | — | `com.bovinelabs.timeline.transform/Sample~/Transform Showcase/Timelines/Position_3.playable` | `sample-mapped` |  |
| `TransformPositionTrack` | `PositionClip` | `UnityEngine` | — | `com.bovinelabs.timeline.physics/Sample~/Swept Trigger Test/SweptTriggerTest.playable (+2)` | `sample-mapped` |  |
| `CarrotTransformTrack` | `CarrotTransformClip` | `UnityEngine` | — | `com.bovinelabs.timeline.transform/Sample~/Transform Showcase/Timelines/Carrot_0.playable` | `sample-mapped` |  |

### com.bovinelabs.timeline.parenting

| Track | Clip | Bind | Soft-gates | Sample | Status | Learned |
|-------|------|------|------------|--------|--------|---------|
| `TemporaryDetachTrack` | `TemporaryDetachClip` | `GameObject` | — | `com.bovinelabs.timeline.parenting/Samples~/Parenting Showcase/Timelines/Seq1_Detach.playable (+2)` | `sample-mapped` |  |

### com.bovinelabs.timeline.entitylinks

| Track | Clip | Bind | Soft-gates | Sample | Status | Learned |
|-------|------|------|------------|--------|--------|---------|
| `EntityLinkMutateTrack` | `EntityLinkMutateClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.entitylinks/Sample~/EntityLinks Showcase/Timelines/Mut2.playable (+2)` | `sample-mapped` |  |
| `EntityLinkParentTrack` | `EntityLinkParentClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.entitylinks/Sample~/EntityLinks Showcase/Timelines/Par1.playable (+1)` | `sample-mapped` |  |
| `EntityLinkCopyTransformTrack` | `EntityLinkCopyTransformClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.entitylinks/Sample~/EntityLinks Showcase/Timelines/Mut2.playable (+2)` | `sample-mapped` |  |
| `EntityLinkTargetPatchTrack` | `EntityLinkTargetPatchClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.entitylinks/Sample~/EntityLinks Showcase/Timelines/Pat0.playable (+1)` | `sample-mapped` |  |

### com.bovinelabs.timeline

| Track | Clip | Bind | Soft-gates | Sample | Status | Learned |
|-------|------|------|------------|--------|--------|---------|
| `SubDirectorTrack` | `SubDirectorClip` | `—` | — | `com.bovinelabs.timeline/Sample~/Timelines/Timeline1.playable` | `sample-mapped` |  |
| `SubDirectorTrack` | `SubTimelineClip` | `—` | — | `com.bovinelabs.timeline/Sample~/Generated/SubTimelineClip_Minimal.playable` | `sample-mapped` | generated minimal playable |

### com.bovinelabs.timeline.audio

| Track | Clip | Bind | Soft-gates | Sample | Status | Learned |
|-------|------|------|------------|--------|--------|---------|
| `ImpactStingerTrack` | `ImpactStingerClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.audio/Sample~/Generated/ImpactStingerClip_Minimal.playable` | `sample-mapped` | generated minimal playable |

### com.bovinelabs.timeline.distance

| Track | Clip | Bind | Soft-gates | Sample | Status | Learned |
|-------|------|------|------------|--------|--------|---------|
| `DistanceToStatTrack` | `DistanceToStatClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.distance/Sample~/Distance Showcase/Timelines/Intv0.playable (+2)` | `sample-mapped` |  |

### com.bovinelabs.timeline.essence

| Track | Clip | Bind | Soft-gates | Sample | Status | Learned |
|-------|------|------|------------|--------|--------|---------|
| `TimelineEssenceIntrinsicTrack` | `TimelineEssenceIntrinsicClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.essence/Sample~/Essence Showcase/Timelines/Intr1.playable (+2)` | `sample-mapped` |  |
| `TimelineEssenceStatTrack` | `TimelineEssenceStatClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.essence/Sample~/Essence Showcase/Timelines/Stat2.playable (+2)` | `sample-mapped` |  |
| `TimelineEssenceTickTrack` | `TimelineEssenceTickClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.essence/Sample~/Essence Showcase/Timelines/Generated/TimelineEssenceTickClip_Minimal.playable` | `sample-mapped` | generated minimal playable |
| `TimelineEssenceEventTrack` | `TimelineEssenceEventClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.essence/Sample~/Essence Showcase/Timelines/Event2.playable (+2)` | `sample-mapped` |  |

### com.bovinelabs.timeline.grid.influence

| Track | Clip | Bind | Soft-gates | Sample | Status | Learned |
|-------|------|------|------------|--------|--------|---------|
| `GridSpawnTrack` | `GridSpawnClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.grid.influence/Sample~/Grid Influence Showcase/Timelines/Generated/GridSpawnClip_Minimal.playable` | `sample-mapped` | generated minimal playable |
| `GridInfluenceTrack` | `GridInfluenceClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.grid.influence/Sample~/Grid Influence Showcase/Timelines/Write2.playable (+2)` | `sample-mapped` |  |
| `GridCompositeTrack` | `GridCompositeClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.grid.influence/Sample~/Grid Influence Showcase/Timelines/Comp1.playable (+2)` | `sample-mapped` |  |
| `GridFlowSteeringTrack` | `GridFlowSteeringClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.grid.influence/Sample~/Grid Influence Showcase/Timelines/Flow0.playable (+2)` | `sample-mapped` |  |

### com.bovinelabs.timeline.particles

| Track | Clip | Bind | Soft-gates | Sample | Status | Learned |
|-------|------|------|------------|--------|--------|---------|
| `ParticleSystemTrack` | `ParticleSystemClip` | `ParticleSystem` | — | `com.bovinelabs.timeline.particles/Sample~/Generated/ParticleSystemClip_Minimal.playable` | `sample-mapped` | generated minimal playable |

### com.bovinelabs.timeline.physics

| Track | Clip | Bind | Soft-gates | Sample | Status | Learned |
|-------|------|------|------------|--------|--------|---------|
| `PhysicsForceTrack` | `PhysicsForceClip` | `PhysicsBodyAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Knockback Reaction/Timelines/Force_3.playable (+2)` | `sample-mapped` |  |
| `PhysicsVelocityTrack` | `PhysicsVelocityClip` | `PhysicsBodyAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Physics/Timeline/Timeline.playable (+2)` | `sample-mapped` |  |
| `PhysicsDragTrack` | `PhysicsDragClip` | `PhysicsBodyAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Force_0.playable (+2)` | `sample-mapped` |  |
| `StatefulTriggerTrack` | `PhysicsTriggerInstantiateClip` | `StatefulTriggerEventAuthoring` | — | `com.bovinelabs.timeline.particles/Sample~/Generated/ParticleSystemClip_Minimal.playable (+2)` | `sample-mapped` | generated minimal playable |
| `StatefulTriggerTrack` | `PhysicsTriggerConditionClip` | `StatefulTriggerEventAuthoring` | — | `com.bovinelabs.timeline.particles/Sample~/Generated/ParticleSystemClip_Minimal.playable (+2)` | `sample-mapped` | generated minimal playable |
| `StatefulTriggerTrack` | `PhysicsTriggerForceClip` | `StatefulTriggerEventAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Swept Trigger Test/SweptTest_Force.playable (+2)` | `sample-mapped` |  |
| `StatefulTriggerTrack` | `PhysicsKnockbackClip` | `StatefulTriggerEventAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Generated/PhysicsKnockbackClip_0.playable` | `sample-mapped` | generated minimal playable |
| `StatefulTriggerTrack` | `PhysicsThrustClip` | `StatefulTriggerEventAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Generated/PhysicsThrustClip_0.playable` | `sample-mapped` | generated minimal playable |
| `StatefulTriggerTrack` | `PhysicsVortexClip` | `StatefulTriggerEventAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Generated/PhysicsVortexClip_0.playable` | `sample-mapped` | generated minimal playable |
| `StatefulTriggerTrack` | `PhysicsBreakForceClip` | `StatefulTriggerEventAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Generated/PhysicsBreakForceClip_0.playable` | `sample-mapped` | generated minimal playable |
| `StatefulTriggerTrack` | `PhysicsTriggerQueryClip` | `StatefulTriggerEventAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Swept Trigger Test/SweptTest_Query.playable (+2)` | `sample-mapped` |  |
| `StatefulTriggerTrack` | `PhysicsTargetSelectClip` | `StatefulTriggerEventAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Generated/PhysicsTargetSelectClip_0.playable` | `sample-mapped` | generated minimal playable |
| `StatefulTriggerTrack` | `PhysicsDirectionalQueryClip` | `StatefulTriggerEventAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Generated/PhysicsDirectionalQueryClip_0.playable` | `sample-mapped` | generated minimal playable |
| `StatefulTriggerTrack` | `PhysicsAoEQueryClip` | `StatefulTriggerEventAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Generated/PhysicsAoEQueryClip_0.playable` | `sample-mapped` | generated minimal playable |
| `PhysicsKinematicOverrideTrack` | `PhysicsKinematicOverrideClip` | `GameObject` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Kin_0.playable (+1)` | `sample-mapped` |  |
| `SocketReturnTrack` | `SocketReturnClip` | `WeaponRecallAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Generated/SocketReturnClip_Minimal.playable` | `sample-mapped` | generated minimal playable |
| `PhysicsShapeSwapTrack` | `PhysicsShapeSwapClip` | `GameObject` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Generated/PhysicsShapeSwapClip_Minimal.playable` | `sample-mapped` | generated minimal playable |
| `PhysicsShapeResizeTrack` | `PhysicsShapeResizeClip` | `GameObject` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Generated/PhysicsShapeResizeClip_Minimal.playable` | `sample-mapped` | generated minimal playable |
| `PhysicsGravityOverrideTrack` | `PhysicsGravityOverrideClip` | `GameObject` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Gravity_2.playable (+2)` | `sample-mapped` |  |
| `PhysicsLinearPIDTrack` | `PhysicsLinearPIDClip` | `PhysicsBodyAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/LinPid_0.playable (+2)` | `sample-mapped` |  |
| `PhysicsAngularPIDTrack` | `PhysicsAngularPIDClip` | `PhysicsBodyAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Sword Swing/SwordSwing.playable (+2)` | `sample-mapped` |  |
| `PhysicsTeleportTrack` | `PhysicsTeleportClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Teleport_0.playable (+2)` | `sample-mapped` |  |
| `PhysicsFilterOverrideTrack` | `PhysicsFilterOverrideClip` | `GameObject` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Filter_0.playable (+1)` | `sample-mapped` |  |
| `SweptTriggerTrack` | `PhysicsTriggerInstantiateClip` | `SweptTriggerSourceAuthoring` | — | `com.bovinelabs.timeline.particles/Sample~/Generated/ParticleSystemClip_Minimal.playable (+2)` | `sample-mapped` | generated minimal playable |
| `SweptTriggerTrack` | `PhysicsTriggerConditionClip` | `SweptTriggerSourceAuthoring` | — | `com.bovinelabs.timeline.particles/Sample~/Generated/ParticleSystemClip_Minimal.playable (+2)` | `sample-mapped` | generated minimal playable |
| `SweptTriggerTrack` | `PhysicsTriggerForceClip` | `SweptTriggerSourceAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Swept Trigger Test/SweptTest_Force.playable (+2)` | `sample-mapped` |  |
| `SweptTriggerTrack` | `PhysicsKnockbackClip` | `SweptTriggerSourceAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Generated/PhysicsKnockbackClip_0.playable` | `sample-mapped` | generated minimal playable |
| `SweptTriggerTrack` | `PhysicsThrustClip` | `SweptTriggerSourceAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Generated/PhysicsThrustClip_0.playable` | `sample-mapped` | generated minimal playable |
| `SweptTriggerTrack` | `PhysicsVortexClip` | `SweptTriggerSourceAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Generated/PhysicsVortexClip_0.playable` | `sample-mapped` | generated minimal playable |
| `SweptTriggerTrack` | `PhysicsBreakForceClip` | `SweptTriggerSourceAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Generated/PhysicsBreakForceClip_0.playable` | `sample-mapped` | generated minimal playable |
| `SweptTriggerTrack` | `PhysicsTriggerQueryClip` | `SweptTriggerSourceAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Swept Trigger Test/SweptTest_Query.playable (+2)` | `sample-mapped` |  |
| `SweptTriggerTrack` | `PhysicsTargetSelectClip` | `SweptTriggerSourceAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Generated/PhysicsTargetSelectClip_0.playable` | `sample-mapped` | generated minimal playable |
| `SweptTriggerTrack` | `PhysicsDirectionalQueryClip` | `SweptTriggerSourceAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Generated/PhysicsDirectionalQueryClip_0.playable` | `sample-mapped` | generated minimal playable |
| `SweptTriggerTrack` | `PhysicsAoEQueryClip` | `SweptTriggerSourceAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Generated/PhysicsAoEQueryClip_0.playable` | `sample-mapped` | generated minimal playable |
| `PhysicsSplineFollowTrack` | `PhysicsSplineFollowClip` | `PhysicsBodyAuthoring` | UNITY_SPLINES | `com.bovinelabs.timeline.physics/Sample~/Spline Follow Example/SplineFollowExample.playable` | `sample-mapped` | soft-gate optional dep |
| `PhysicsVelocityClampTrack` | `PhysicsVelocityClampClip` | `GameObject` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Clamp_0.playable (+2)` | `sample-mapped` |  |
| `PhysicsRicochetTrack` | `PhysicsRicochetClip` | `GameObject` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Ricochet_0.playable (+1)` | `sample-mapped` |  |
| `ChainFollowTrack` | `ChainFollowClip` | `ChainWeaponAuthoring` | — | `com.bovinelabs.timeline.physics/Sample~/Physics Showcase/Timelines/Generated/ChainFollowClip_Minimal.playable` | `sample-mapped` | generated minimal playable |

### com.bovinelabs.timeline.playerinputs

| Track | Clip | Bind | Soft-gates | Sample | Status | Learned |
|-------|------|------|------------|--------|--------|---------|
| `NavFlowInputTrack` | `NavFlowInputClip` | `TargetsAuthoring` | BL_MOVEMENT | `com.bovinelabs.timeline.playerinputs/Sample~/PlayerInputs Showcase/Timelines/Generated/NavFlowInputClip_Minimal.playable` | `sample-mapped` | generated minimal playable; soft-gate optional dep |
| `ControlOverrideTrack` | `ControlOverrideClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.playerinputs/Sample~/PlayerInputs Showcase/Timelines/Generated/ControlOverrideClip_Minimal.playable` | `sample-mapped` | generated minimal playable |
| `AxisTransformTrack` | `AxisTransformClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.playerinputs/Sample~/PlayerInputs Showcase/Timelines/Axis0.playable (+2)` | `sample-mapped` |  |
| `InputBufferTrack` | `InputBufferWindowClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.playerinputs/Sample~/PlayerInputs Showcase/Timelines/Cmd1_Motion.playable (+2)` | `sample-mapped` |  |
| `InputBufferTrack` | `InputBufferClearClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.playerinputs/Sample~/PlayerInputs Showcase/Timelines/Buf1_ClearWindow.playable (+1)` | `sample-mapped` |  |
| `InputEventsTrack` | `InputEventsClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.playerinputs/Sample~/PlayerInputs Showcase/Timelines/Evt0_Edges.playable` | `sample-mapped` |  |
| `SplineFlowInputTrack` | `SplineFlowInputClip` | `TargetsAuthoring` | UNITY_SPLINES | `com.bovinelabs.timeline.playerinputs/Sample~/PlayerInputs Showcase/Timelines/Generated/SplineFlowInputClip_Minimal.playable` | `sample-mapped` | generated minimal playable; soft-gate optional dep |
| `CommandSequenceTrack` | `CommandSequenceClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.playerinputs/Sample~/PlayerInputs Showcase/Timelines/Cmd1_Motion.playable (+1)` | `sample-mapped` |  |
| `FlowInputTrack` | `FlowInputClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.playerinputs/Sample~/PlayerInputs Showcase/Timelines/Flow0.playable (+2)` | `sample-mapped` |  |

### com.bovinelabs.timeline.time

| Track | Clip | Bind | Soft-gates | Sample | Status | Learned |
|-------|------|------|------------|--------|--------|---------|
| `TimelineTimeScaleTrack` | `TimelineTimeScaleClip` | `StatAuthoring` | — | `com.bovinelabs.timeline.time/Sample~/Time Showcase/Timelines/PT3.playable (+2)` | `sample-mapped` |  |
| `WorldTimeScaleTrack` | `WorldTimeScaleClip` | `—` | — | `com.bovinelabs.timeline.time/Sample~/SlowMo Demo/SlowMoTimeline.playable (+2)` | `sample-mapped` |  |
| `TimelineTimeJumpTrack` | `TimelineTimeJumpClip` | `TargetsAuthoring` | — | `com.bovinelabs.timeline.time/Sample~/Time Showcase/Timelines/Generated/TimelineTimeJumpClip_Minimal.playable` | `sample-mapped` | generated minimal playable |

### com.bovinelabs.timeline.ui

| Track | Clip | Bind | Soft-gates | Sample | Status | Learned |
|-------|------|------|------------|--------|--------|---------|
| `UxmlViewTrack` | `UxmlViewClip` | `—` | — | `com.bovinelabs.timeline.ui/Sample~/UI Showcase/Timelines/Uxml1.playable (+1)` | `sample-mapped` |  |
| `DataDisplayTrack` | `DataDisplayClip` | `Transform` | — | `com.bovinelabs.timeline.ui/Sample~/UI Showcase/Timelines/Data0.playable` | `sample-mapped` |  |
| `UIBindOverrideTrack` | `UIBindOverrideClip` | `—` | — | `com.bovinelabs.timeline.ui/Sample~/UI Showcase/Timelines/Generated/UIBindOverrideClip_Minimal.playable` | `sample-mapped` | generated minimal playable |
| `UITextRevealTrack` | `UITextRevealClip` | `—` | — | `com.bovinelabs.timeline.ui/Sample~/UI Showcase/Timelines/Reveal0.playable (+1)` | `sample-mapped` |  |
| `NumberTrack` | `NumberClip` | `—` | — | `com.bovinelabs.timeline.ui/Sample~/UI Showcase/Timelines/Number0.playable (+1)` | `sample-mapped` |  |
| `EssenceUITrack` | `EssenceUIClip` | `StatAuthoring` | — | `com.bovinelabs.timeline.ui/Sample~/UI Showcase/Timelines/Essence0.playable` | `sample-mapped` |  |
| `UssClassTrack` | `UssClassClip` | `—` | — | `com.bovinelabs.timeline.ui/Sample~/UI Showcase/Timelines/Uss0.playable` | `sample-mapped` |  |

## Builds / artifacts

Per-package sample zips under `Builds/dist/timeline-showcase-*.zip` (local).

## Exhausted-impossible

| Item | Reason | Attempts |
|------|--------|----------|
| NavFlowInputClip full runtime | Needs `BL_MOVEMENT` / com.bovinelabs.movement (not in host) | Sample playable authored; runtime soft-gated `#if BL_MOVEMENT` |
| SplineFlowInputClip full runtime | Needs `UNITY_SPLINES` | Sample playable authored; runtime soft-gated |
| PhysicsSplineFollow full path bake | Needs Unity Splines package | Gallery has spline example when package present |
| Headless gameplay video | No reliable compositor for Timeline bake→player video without GPU editor session | Attempted/plan: ffmpeg x11grab when DISPLAY+editor play works |

## Journey log

- Scanned Authoring TrackClipType across all timeline packages (82 clips).
- Mapped existing Sample~/Gallery/Demo playables via EditorClassIdentifier/m_Name.
- Generated minimal playables for gaps (physics trigger family, carrot, tick, time jump, particles, audio, bind override, control override, soft-gate flows, subtimeline stub).
- Packaged Sample folders into Builds/dist zips for offline release if rate-limited.
- Added EditMode structural coverage test: `TimelineSampleCoverageTests`.
