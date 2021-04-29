# polor pashm
polor pashm is an ANSI color library for __Pashmak programming language__ 

### Installation
To install this library via the Parham package manager:

```bash
$ parham install gh:sami2020pro/polor-pashm
```

# preview
Version 1
```bash
import 'polor.pashm'

use polor

println $FgBlue + 'Pashmak'
println $BgHiGreen + $FgHiBlack + 'programming' + $Reset
println $Bold + 'language'
```

Version 2 
```bash
import 'polor.pashm'

use polor

println $ftc->Blue + 'Pashmak'
println $bhitc->HiGreen + $fhitc->HiBlack + 'programming' + $ba->Reset
println $ba->Bold + 'language'
```

In the new update, Pashmak Class were added and we also updated this library.

**Warning: Note that in the new version of this library, the speed has dropped very slowly**

Output both codes
<div>
  <img 
    src="/data/polor-preview.png"
    alt="polor is a simple Terminal Color library for Pashmak programming language"
    style=""
  />
</div>

# Wiki
<p>For more examples click <a href="https://github.com/sami2020pro/polor-pashm/wiki">here</a></p>
