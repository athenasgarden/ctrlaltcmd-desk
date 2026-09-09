# CTRL+ALT+CMD field kit

Clone it. Fill a session. Commit the experiment folder. That is the work.

```
git clone https://github.com/athenasgarden/ctrlaltcmd-desk.git
cd ctrlaltcmd-desk
```

## Layout

```
interrupt/SESSION.md          copy to interrupt/YYYY-MM-DD.md
signal/PASS.md                run on model output before you keep it
experiment/_template/         copy to experiment/YYYY-MM-DD-slug/
experiment/2026-09-09-field-kit/   a finished example (this kit)
```

## Cycle

1. Copy the interrupt session. 25 minutes. Four lines. Close the other tabs.
2. If the object is model text, run the signal pass on it.
3. If the object is a question you can finish today:

```
cp -r experiment/_template experiment/$(date +%F)-short-slug
```

Fill QUESTION.md first. Make the artifact. Fill AFTER.md. Commit that folder.

Git history is the log.

Editorial notes for creators and operators. The kit is the product on this domain.
