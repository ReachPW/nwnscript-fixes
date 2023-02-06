# nwnscript-fixes





# Changes

## x0_i0_anims.nss

Fixed function declaration to remove warning when compiling under nwnsc

Before: 
`(1261): Warning: NSC6023: Function "AnimActionPlayRandomGreeting" argument "nHDiff" default value does not match the initializer value for a previous declaration.  The first declaration value will be used.`

After:  [no warning]


## x2_inc_switches

Fixed function declaration to remove warning when compiling under nwnsc

Before: 
`x2_inc_switches.nss(596): Warning: NSC6023: Function "SetExecutedScriptReturnValue" argument "nValue" default value does not match the initializer value for a previous declaration.  The first declaration value will be used.`
`

After:  [no warning]

## x2_inc_restsys

Fixed function declaration to remove warning when compiling under nwnsc

Before: 
`x2_inc_restsys.nss(685): Warning: NSC6023: Function "WMSetAreaTable" argument "nListenCheckDC" default value does not match the initializer value for a previous declaration.  The first declaration value will be used.`

After:  [no warning]