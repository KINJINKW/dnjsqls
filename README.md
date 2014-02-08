[Public]
Object[0]=(Name=Engine.ServerCommandlet,Class=Class,MetaClass=Core.Commandlet)
Object[1]=(Name=Engine.MasterMD5Commandlet,Class=Class,MetaClass=Core.Commandlet)
Object[2]=(Name=Engine.SmokeTestCommandlet,Class=Class,MetaClass=Core.Commandlet)

[Errors]
NetHDSpace=There is not enough space on your HDD to download the package. You will need to free some space to download packages.
NetOpen=Error opening file
NetWrite=Error writing to file
NetRefused=Server refused to send '`~'
NetClose=Error closing file
NetSize=File size mismatch
NetMove=Error moving file
NetInvalid=Received invalid file request
NoDownload=Package '`~' is not downloadable
DownloadFailed=Downloading package '`~' failed: `~
RequestDenied=Server requested file from pending level: Denied
ConnectionFailed_Title=Connection Lost
ConnectionFailed=Your connection to the host has been lost.
ChAllocate=Couldn't allocate channel
NetAlready=Already networking
NetListen=Listen failed: No linker context available
LoadEntry=Can't load Entry: `~
InvalidUrl=Invalid URL: `~
InvalidLink=Invalid Link: `~
FailedBrowse=Failed to enter `~: `~. Please check the log for errors.
Listen=Listen failed: `~
AbortToEntry=Failed; returning to Entry
ServerOpen=Servers can't open network URLs
ServerListen=Dedicated server can't listen: `~
Pending=Pending connect to '`~' failed; `~
LoadPlayerClass=Failed to load player class
ClientOutdated=The match you are trying to join is running an incompatible version of the game.  Please try upgrading your game version.
ServerOutdated=Server's version is outdated
FailedMapload_NotFound=The map specified on the commandline '`~' could not be found. Would you like to load the default map instead?
DebuggerPresentError=The game has detected that you are currently running a user-mode or kernel-mode debugger and cannot continue.  Please exit all debugging utilities and restart the game.
NetworkInit=Error initializing network layer.
CreateMatchError=Error creating match
UsedCheatCommands=Console commands were used which are disallowed in netplay.  You must restart the game to create a match.
FailedFindPackage=Failed to find required package '`~'
ConnectionTimeout=Your connection to the host timed out
NegativeDeltaTime=CPU time drift detected! Please consult release notes on how to address this.

[Progress]
CancelledConnect=Cancelled Connect Attempt
RunningNet=`~: `~ (`~ players)
NetReceiving=Receiving '`~': `~/`~
NetReceiveOk=Successfully received '`~'
NetSend=Sending '`~'
NetSending=Sending '`~': `~/`~
Connecting=Connecting…
Listening=Listening for clients…
Loading=Loading
Saving=Saving
Paused=Paused by `~
ReceiveFile=Receiving '`~'
ReceiveOptionalFile=Receiving optional file '`~'
ReceiveSize=Size `~K, Complete `3.1~`~
ConnectingText=Connecting:
ConnectingURL=unreal://`~/`~
Success=Success

[Console]
ClassCaption=Standard Unreal Console

[GameViewportClient]
LoadingMessage=LOADING
SavingMessage=SAVING
ConnectingMessage=CONNECTING
PausedMessage=PAUSED
PrecachingMessage=PRECACHING

[MasterMD5Commandlet]
HelpCmd=mastermd5
HelpOneLiner=Manipulate the Master MD5 database
HelpUsage=mastermd5 [-option..] <params>
HelpWebLink=http://unreal.epicgames.com/servertips.htm
HelpParm[0]=-c
HelpDesc[0]=Creates a new MD5 database
HelpParm[1]=-a
HelpDesc[1]=Adds new packages to the database
HelpParm[2]=-s
HelpDesc[2]=Show the current database.
HelpParm[3]=-r
HelpDesc[3]=Force the revision of all entries to <param>

[General]
Upgrade=To enter this server, you need the latest free update to Unreal available from Epic's Web site:
UpgradeURL=http://www.unreal.com/upgrade
UpgradeQuestion=Do you want to launch your web browser and go to the upgrade page now?
Version=Version `~

[Menu]
HelpMessage=
MenuList=
LeftString=Left
RightString=Right
CenterString=Center
EnabledString=Enabled
DisabledString=Disabled
HelpMessage[1]=This menu has not yet been implemented.
YesString=yes
NoString=no

[PlayerController]
QuickSaveString=Quick Saving
NoPauseMessage=Game is not pauseable
ViewingFrom=Now viewing from
OwnCamera=Now viewing from own camera

[DamageType]
DeathString=`o was killed by `k.
FemaleSuicide=`o killed herself.
MaleSuicide=`o killed himself.

[DmgType_Suicided]
DeathString=`o had an aneurysm.
FemaleSuicide=`o had an aneurysm.
MaleSuicide=`o had an aneurysm.

[GameInfo]
DefaultPlayerName=Player
GameName=Game

[HUD]
LoadingMessage=LOADING
SavingMessage=SAVING
ConnectingMessage=CONNECTING
PausedMessage=PAUSED

[Inventory]
PickupMessage=Snagged an item.

[LevelInfo]
Title=Untitled

[PlayerReplicationInfo]
StringDead=Dead
StringSpectating=Spectating
StringUnknown=Unknown

[TeamInfo]
TeamName=Team

[Weapon]
ItemName=Weapon

[GameMessage]
SwitchLevelMessage=Switching Levels
LeftMessage=" left the game."
FailedTeamMessage=Could not find team for player
FailedPlaceMessage=Could not find a starting spot
FailedSpawnMessage=Could not spawn player
EnteredMessage=" entered the game."
MaxedOutMessage=Server is already at capacity.
ArbitrationMessage=The session has already started.
OvertimeMessage=Score tied at the end of regulation. Sudden Death Overtime!!!
GlobalNameChange=changed name to
NewTeamMessage=is now on
NoNameChange=Name is already in use.
VoteStarted=started a vote.
VotePassed=Vote passed.
MustHaveStats=Must have stats enabled to join this server.
CantBeSpectator=Sorry, you cannot become a spectator at this time.
CantBePlayer=Sorry, you cannot become an active player at this time.
BecameSpectator=became a spectator.
NewPlayerMessage=A new player entered the game.
KickWarning=You are about to be kicked for idling!
NewSpecMessage=A spectator entered the game/
SpecEnteredMessage=" joined as a spectator."

[WaterVolume]
LocationName=under water

[DmgType_Telefragged]
DeathString=`o was telefragged by `k
FemaleSuicide=`o was telefragged by `k
MaleSuicide=`o was telefragged by `k

[DmgType_Fell]
DeathString=`k pushed `o over the edge.
FemaleSuicide=`o left a small crater
MaleSuicide=`o left a small crater

[FailedConnect]
FailMessage[0]=FAILED TO JOIN GAME.  NEED PASSWORD.
FailMessage[1]=FAILED TO JOIN GAME.  WRONG PASSWORD.
FailMessage[2]=FAILED TO JOIN GAME.  GAME HAS STARTED.
FailMessage[3]=FAILED TO JOIN GAME.

[AccessControl]
IPBanned=Your IP address has been banned on this server.
WrongPassword=The password you entered is incorrect.
NeedPassword=You need to enter a password to join this game.
SessionBanned=Your IP address has been banned from the current game session.
KickedMsg=You have been forcibly removed from the game.
DefaultKickReason=None specified
IdleKickReason=Kicked for idling.
ACDisplayText[0]=Game Password
ACDisplayText[1]=Access Policies
ACDisplayText[2]=Admin Password
ACDescText[0]=If this password is set, players will have to enter it to join this server.
ACDescText[1]=Specifies IP addresses or address ranges which have been banned.
ACDescText[2]=Password required to login with administrator privileges on this server.

[ServerCommandlet]
HelpDescription=Network game server
HelpUsage=server map.unr[?game=gametype] [-option…] [parm=value]…
HelpWebLink=http://unreal.epicgames.com/servertips.htm
HelpParamNames[0]=Log
HelpParamDescriptions[0]=Specify the log file to generate
HelpParamNames[1]=AllAdmin
HelpParamDescriptions[1]=Give all players admin privelages

[UIEditBox]
InitialValue=Initial Editbox Value

[UIStyle]
StyleName=Default Style

[UIStyle_Text]
StyleName=Default Text Style

[UIStyle_Image]
StyleName=Default Image Style

[ConsoleTextStyle]
StyleName=Console Text Style

[ConsoleImageStyle]
StyleName=Console Border Style

[ConsoleStyle]
StyleName=Console Combo Style

[ConsoleBufferTextStyle]
StyleName=Console Buffer Text Style

[ConsoleBufferTextImageStyle]
StyleName=Console Buffer Background Style

[ConsoleBufferStyle]
StyleName=Console Buffer Combo Style

[CursorImageStyle]
StyleName=Cursor Style

[UIEvent_ProcessInput]
DisplayName=Process Input
Description=Executes actions in response to an input event, such as a keypress or mouse movement

[UIEvent_OnEnterState]
DisplayName=Enter State
Description=Activated whenever a widget enters a new menu state, such as disabled or focused

[UIEvent_OnLeaveState]
DisplayName=Leave State
Description=Activated whenever a widget leaves a menu state, such as disabled or focused

[UINumericEditBox]
IncrementButtonName="Increment Button"
DecrementButtonName="Decrement Button"

[SmokeTestCommandlet]
HelpDescription=This commandlet runs a series of tests to validate a build
HelpUsage=gamename.exe smoketest <SERVER | CHECK_NATIVE_CLASS_SIZES>
HelpWebLink=
HelpParamNames[0]=SERVER
HelpParamDescriptions[0]=Runs the game as a server for one tick to validate startup and first frame code
HelpParamNames[1]=CHECK_NATIVE_CLASS_SIZES
HelpParamDescriptions[1]=Validates that all native classes match their script classes in member layout

[ExampleGameMenu]
CancelButtonText=Return To Game
RespawnButtonText=Respawn Player
ReloadButtonText=Reload Map
InlineFontSampleText=These words are small… <Fonts:EngineFonts.LargeFont>these words are big,<Fonts:/> and these words are back to normal.
InlineStyleSampleText=These words are normal… <Styles:ConsoleStyle>these words are green<Styles:/> and these words are normal too.
SplitscreenButtonText=Splitscreen Test Scene

[TestMenuStrings]
ButtonTestText=The button has been clicked <SceneData:ButtonClickCount> times.
PlayerIndexText=The propagated PlayerIndex is: <SceneData:PlayerIndex>.
WrapStringTest=This is just some nonsense text that will be used for testing various string auto-sizing features. This really long string is a great one to use for testing the wrapping functionality of a UIString.  In fact, there are so many characters in this string that it is great for testing many different features of a UIString.

[OnlineProfileSettings]
OwnerMappings[0]=(Name="None")
OwnerMappings[1]=(Name="Online Service Setting")
OwnerMappings[2]=(Name="Game Setting")
ProfileMappings[0]=(ValueMappings=((Name="Off"),(Name="On")))
ProfileMappings[1]=(ValueMappings=((Name="Off"),(Name="On")))
ProfileMappings[2]=(ValueMappings=((Name="No"),(Name="Yes")))
ProfileMappings[3]=(ValueMappings=((Name="Off"),(Name="On"),(Name="Both")))
ProfileMappings[5]=(ValueMappings=((Name="Normal"),(Name="Easy"),(Name="Hard")))
ProfileMappings[6]=(ValueMappings=((Name="Medium"),(Name="Low"),(Name="High")))
ProfileMappings[7]=(ValueMappings=((Name="None"),(Name="Black"),(Name="White"),(Name="Yellow"),(Name="Orange"),(Name="Pink"),(Name="Red"),(Name="Purple"),(Name="Blue"),(Name="Green"),(Name="Brown"),(Name="Silver")))
ProfileMappings[8]=(ValueMappings=((Name="None"),(Name="Black"),(Name="White"),(Name="Yellow"),(Name="Orange"),(Name="Pink"),(Name="Red"),(Name="Purple"),(Name="Blue"),(Name="Green"),(Name="Brown"),(Name="Silver")))
ProfileMappings[9]=(ValueMappings=((Name="Off"),(Name="On")))
ProfileMappings[10]=(ValueMappings=((Name="Off"),(Name="On")))
ProfileMappings[11]=(ValueMappings=((Name="Left Thumbstick"),(Name="Right Thumbstick")))
ProfileMappings[12]=(ValueMappings=((Name="Auto"),(Name="Manual")))
ProfileMappings[13]=(ValueMappings=((Name="Behind"),(Name="Front"),(Name="Inside")))
ProfileMappings[14]=(ValueMappings=((Name="Trigger"),(Name="Button")))
ProfileMappings[15]=(ValueMappings=((Name="Trigger"),(Name="Button")))

[ViewportStatus]
RenderingFrozenE=Rendering frozen…
OcclusionChild=Occlusion Child

[UIDataProvider_OnlineFriendMessages]
SendingPlayerNameCol=Sender's Name
bIsFriendInviteCol=Friend Invitation
bWasAcceptedCol=Friend Was Accepted
bWasDeniedCol=Friend Was Denied
MessageCol=Message

[UIDataProvider_OnlineFriends]
NickNameCol=Name
PresenceInfoCol=Online Status
bIsOnlineCol=Is Online
bIsPlayingCol=Is Playing
bIsPlayingThisGameCol=Is Playing This Game
bIsJoinableCol=Is Joinable
bHasVoiceSupportCol=Has Voice Support

[OnlineGameSettings]
NumPublicConnections.FriendlyName="Max Public Slots"
NumPrivateConnections.FriendlyName="Max Private Slots"
NumOpenPublicConnections.FriendlyName="Open Public Slots"
NumOpenPrivateConnections.FriendlyName="Open Private Slots"
bShouldAdvertise.FriendlyName="Advertise"
bIsLanMatch.FriendlyName="Lan Match"
bUsesStats.FriendlyName="Uses Stats"
bAllowJoinInProgress.FriendlyName="Join In Progress Allowed"
bAllowInvites.FriendlyName="Invites Allowed"
bUsesPresence.FriendlyName="Presence Enabled"
bAllowJoinViaPresence.FriendlyName="Join Via Presence Allowed"
bUsesArbitration.FriendlyName="Arbitration"
OwningPlayerName.FriendlyName="Server"
PingInMs.FriendlyName="Ping"
bIsDedicated.FriendlyName="Dedicated"
bIsListPlay.FriendlyName="ListPlay"
AverageSkillRating.FriendlyName="Skill Rating"

[UIDataStore_OnlineStats]
PlayerNickData.PlayerNickColumnName="Player Nick"
RankNameMetaData.RankColumnName="Rank"

