# Expansion Checkpoint Integrity Audit (Local Compute)
Generated: 2026-03-06T04:02:43.664880-05:00

## Inventory counts
- 2026-03-05-full-raw-checkpoint-1: 714
- EXHAUSTIVE_CONSOLIDATION_2026-03-06_v3: 15017
- EXHAUSTIVE_CONSOLIDATION_2026-03-06_v4: 3004

## SHA256 manifest state
- 2026-03-05-full-raw-checkpoint-1: size=103431 lines=714
- EXHAUSTIVE_CONSOLIDATION_2026-03-06_v3: size=0 lines=0
- EXHAUSTIVE_CONSOLIDATION_2026-03-06_v4: size=0 lines=0

## Drift/new deltas
- 2026-03-05-full-raw-checkpoint-1 -> EXHAUSTIVE_CONSOLIDATION_2026-03-06_v4: new=2822 removed=714 drift=0
- EXHAUSTIVE_CONSOLIDATION_2026-03-06_v3 -> EXHAUSTIVE_CONSOLIDATION_2026-03-06_v4: new=15 removed=9752 drift=16

## Spot SHA256: 2026-03-05-full-raw-checkpoint-1
- idx 0: PASS | data/home/.openclaw/agents/main/agent/._auth-profiles.json | 68f667117ff789307989a06da542e437aa4361f0a2fe8a4c247666dd500aeea8
- idx 178: PASS | data/home/.openclaw/workspace/.git/config | cae33efdb02cf774435c1ff9cb16bcc1014606908530c6e1dc727615fe3e8cda
- idx 357: PASS | data/workspace/workspace/.git/objects/8c/ddf5a81b5b4e9a4335f64f4dbe62464080e706 | ac15d32f9eaeb9a7c85d4228640857e4eaae3b613625e7cbd995f33e20e16c2b
- idx 535: PASS | data/obsidian/OpenClaw/Backups/2026-02-26-monetization-agent-stack-v3/skills/ai-video-postproduction-studio/references/._ai-video-and-postproduction-stack.md | 68f667117ff789307989a06da542e437aa4361f0a2fe8a4c247666dd500aeea8
- idx 713: PASS | data/obsidian/._OpenClaw | 68f667117ff789307989a06da542e437aa4361f0a2fe8a4c247666dd500aeea8

## Spot SHA256: EXHAUSTIVE_CONSOLIDATION_2026-03-06_v3
- idx 0: ERROR | /Users/tydroelite/.openclaw/exec-approvals.json | [Errno 2] No such file or directory: '/Volumes/Expansion/OpenClaw/centralized-checkpoints/EXHAUSTIVE_CONSOLIDATION_2026-03-06_v3/RAW/Users_tydroelite_.openclaw/exec-approvals.json'
- idx 3754: ERROR | /Volumes/Expansion/.openclaw/media/inbound/._file_62---18e97b80-b81d-438b-b6c4-7c9aefb197e4.zip | [Errno 2] No such file or directory: '/Volumes/Expansion/OpenClaw/centralized-checkpoints/EXHAUSTIVE_CONSOLIDATION_2026-03-06_v3/RAW/Volumes_Expansion_.openclaw/media/inbound/._file_62---18e97b80-b81d-438b-b6c4-7c9aefb197e4.zip'
- idx 7508: ERROR | /Volumes/Expansion/.openclaw/browser/openclaw/user-data/Default/shared_proto_db/metadata/._MANIFEST-000001 | [Errno 2] No such file or directory: '/Volumes/Expansion/OpenClaw/centralized-checkpoints/EXHAUSTIVE_CONSOLIDATION_2026-03-06_v3/RAW/Volumes_Expansion_.openclaw_browser_openclaw/user-data/Default/shared_proto_db/metadata/._MANIFEST-000001'
- idx 11262: ERROR | /Volumes/Expansion/LOGIC UNIVERSE/audio PLUGZ/Cymatics - Keys (v1.0.0)/Sources/Synth - Memory/Memory Moog Synth - Memory Moog Synth - Velocity 41 - 068 - g#3.wav | [Errno 2] No such file or directory: '/Volumes/Expansion/OpenClaw/centralized-checkpoints/EXHAUSTIVE_CONSOLIDATION_2026-03-06_v3/RAW/Volumes_Expansion_LOGIC_UNIVERSE_audio_PLUGZ_Cymatics_-_Keys__v1.0.0__Sources_Synth_-_Memory/Memory Moog Synth - Memory Moog Synth - Velocity 41 - 068 - g#3.wav'
- idx 15016: ERROR | /Volumes/Expansion/OPENCLAW EVERYTHING FILE/openclaw_workspace/node_modules/@ark/util/out/registry.d.ts | [Errno 2] No such file or directory: '/Volumes/Expansion/OpenClaw/centralized-checkpoints/EXHAUSTIVE_CONSOLIDATION_2026-03-06_v3/RAW/Volumes_Expansion_OPENCLAW_EVERYTHING_FILE/openclaw_workspace/node_modules/@ark/util/out/registry.d.ts'

## Spot SHA256: EXHAUSTIVE_CONSOLIDATION_2026-03-06_v4
- idx 0: PASS | /Users/tydroelite/.openclaw/.openclaw/agents/main/agent/models.json | b44a11b5973125947ad7e6bc04bbd6722f34a37dbdebec94d393c4c115dd28a1
- idx 751: PASS | /Volumes/Expansion/.openclaw/agents/ga-createshinnsllc/sessions/8be406ad-2d25-4005-8a5b-9189d8e57cd1.jsonl.reset.2026-02-26T08-14-51.314Z | 2ffbc02d9dfcb6994953cb5d5e76a42b627adb5e75f0d6cf831ec0696841007a
- idx 1502: PASS | /Volumes/Expansion/.openclaw/browser/openclaw/user-data/Default/Cache/._Cache_Data | 35f5c2cfcc52685fe216997c7ed2240295f34ad5c235d1931f5cf080bf71a29c
- idx 2253: PASS | /Volumes/Expansion/.openclaw/identity/device-auth.json | 2c34656c3cc7055345828d40ea375926f1a54f1f0230986bd83672cb5bee00a8
- idx 3003: PASS | /Volumes/Expansion/.openclaw/sandboxes/agent-ga-tydroelite1-cdb81c0d/skills/sherpa-onnx-tts/bin/sherpa-onnx-tts | 542d46f42f5ff8d22ed71f58ca052e4e525a337d90bd25664a6237b6da56fd2a
