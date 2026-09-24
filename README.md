# ghub-practice


Usage: ghub branch [OPTIONS] NAME
Try 'ghub branch --help' for help.

Error: Got unexpected extra arguments (special is beeing done)
mohammadsadiq@Mohammads-MacBook-Air ghub-practice % g branches                           
Switch to which branch?
┌───┬───────────┬───────────┐
│ # │ Branch    │ Status    │
├───┼───────────┼───────────┤
│ 1 │ main      │ local     │
│ 2 │ quicktest │ ★ current │
└───┴───────────┴───────────┘
  0. Cancel
Enter a number: 2
❌ Command failed: git pull origin quicktest
fatal: couldn't find remote ref quicktest
✅ Switched to 'quicktest'.
mohammadsadiq@Mohammads-MacBook-Air ghub-practice % g branches                          
Switch to which branch?
┌───┬───────────┬───────────┐
│ # │ Branch    │ Status    │
├───┼───────────┼───────────┤
│ 1 │ main      │ local     │
│ 2 │ quicktest │ ★ current │
└───┴───────────┴───────────┘
  0. Cancel
Enter a number: 1
✅ Switched to 'main'.
mohammadsadiq@Mohammads-MacBook-Air ghub-practice % g push
Commit message (required): ...
✅ Pushed to 'main' — 1 file changed, 1 insertion(+), 1 deletion(-)
mohammadsadiq@Mohammads-MacBook-Air ghub-practice % g branches
Switch to which branch?
┌───┬───────────┬───────────┐
│ # │ Branch    │ Status    │
├───┼───────────┼───────────┤
│ 1 │ main      │ ★ current │
│ 2 │ quicktest │ local     │
└───┴───────────┴───────────┘
  0. Cancel
Enter a number: 2
❌ Command failed: git pull origin quicktest
fatal: couldn't find remote ref quicktest
✅ Switched to 'quicktest'.
mohammadsadiq@Mohammads-MacBook-Air ghub-practice % g branches
Switch to which branch?
┌───┬───────────┬───────────┐
│ # │ Branch    │ Status    │
├───┼───────────┼───────────┤
│ 1 │ main      │ local     │
│ 2 │ quicktest │ ★ current │
└───┴───────────┴───────────┘
  0. Cancel
Enter a number: 