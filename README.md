# CBT136
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)

This is still a work in progress. GitHub repos will be deleted and created during this period...

```
//***FILE 136 is from Mr Howard Dean of Alameda, California.        *   FILE 136
//*           THIS FILE IS IN IEBUPDTE SYSIN FORMAT AND             *   FILE 136
//*           CONTAINS THE FOLLOWING MEMBERS:  FOR ADDITIONAL       *   FILE 136
//*           INFORMATION SEE THE MEMBER CALLED $INDEX              *   FILE 136
//*                                                                 *   FILE 136
//*       Howard Dean has contributed another file, CBT File 119,   *   FILE 136
//*       which is of earlier date than this file.  When looking    *   FILE 136
//*       at programs from this file, CBT File 119 may also be      *   FILE 136
//*       a useful reference to look at, but this file is later.    *   FILE 136
//*                                                                 *   FILE 136
//*       further support:  Sam Golob                               *   FILE 136
//*                 email:  sbgolob@cbttape.org                     *   FILE 136
//*                                                                 *   FILE 136
//*           AAHLXXX       WTO EXIT FOR CERTAIN 'GTF' MESSAGES     *   FILE 136
//*           ADFHXXX       WTO EXIT TO PROCESS CICS JOURNALS       *   FILE 136
//*           AFNMXXX       WTO EXIT TO PROCESS NDM LOG SWITCH      *   FILE 136
//*           AIEAXXX       WTO EXIT TO KICK OFF JOB TO COPY        *   FILE 136
//*                         SYS1.DUMPXX TO IPCS                     *   FILE 136
//*           AIEEXXX       WTO EXIT TO HIGHLIGHT SMF DATASET       *   FILE 136
//*                         ERRORS                                  *   FILE 136
//*           APLCAMS       PROGRAM TO CALL IDCAMS TO ALLOW VSAM    *   FILE 136
//*                         ALLOCATION ON SYSDA                     *   FILE 136
//*           APUT          MACRO TO CALL EPUTL FOR ASID TSO        *   FILE 136
//*                         COMMAND                                 *   FILE 136
//*           ASID          TSO/E COMMAND TO SHOW ADDRESS SPACE     *   FILE 136
//*                         DATA (31-BIT MODE)                      *   FILE 136
//*           BANNER        BLOCK PRINT PARM FIELD (REQUIRES        *   FILE 136
//*                         'SYS1.AOSB0(IEFSD095)')                 *   FILE 136
//*           BRODCAST      PROGRAM TO SCAN 'SYS1.BRODCAST' DATASET *   FILE 136
//*                         AND REPORT                              *   FILE 136
//*           CARTCOPY      PROGRAM GENERATE JCL TO CALL CARTPROC   *   FILE 136
//*                         AND INVOKE NEWVOL                       *   FILE 136
//*           CARTPROC      CATALOGED PROCEDURE USED WITH CARTCOPY  *   FILE 136
//*           CONSOLE       TSO COMMAND TO DISPLAY THE OPERATOR     *   FILE 136
//*                         CONSOLE (XA 2.2)                        *   FILE 136
//*           CPPL          MACRO TO GENERATE TSO CPPL BLOCK        *   FILE 136
//*           CSPL          MACRO TO GENERATE TSO CSPL BLOCK        *   FILE 136
//*           DATECONV      CONVERT JULIAN DATE TO GREGORIAN        *   FILE 136
//*           DRDROID       VTAM DYNAMIC RECONFIGURATION DECK       *   FILE 136
//*                         BUILDER                                 *   FILE 136
//*           ENTER         MACRO FOR ENTRY TO PROGRAM (SAVE        *   FILE 136
//*                         REGISTERS, ETC..)                       *   FILE 136
//*           EPUTL         ROUTINE TO SET UP TEXT AND CALL PUTLINE *   FILE 136
//*                         FOR ASID COMMAND                        *   FILE 136
//*                         (Cleaned up a bit by Sam Golob.)        *   FILE 136
//*           HMDCHRON      TIME KEEPER SUPREME (RETURNS TOD IN     *   FILE 136
//*                         VARIOUS FORMATS)                        *   FILE 136
//*           HMDTIME       MACRO TO MAP HMDCHRON 72 BYTE RETURN    *   FILE 136
//*                         AREA                                    *   FILE 136
//*           IKJEFF10      TSO/E SUBMIT EXIT--MODIFIES JOBNAME,    *   FILE 136
//*                         NOTIFY ACF2 LOGONID                     *   FILE 136
//*           INMXZ02       TSO/E XMIT EXIT TO NOTIFY USER ON SAME  *   FILE 136
//*                         SYSTEM OF MAIL                          *   FILE 136
//*           INUSE         MACRO TO SHOW REGISTERS ASSIGNED BY     *   FILE 136
//*                         LUSE                                    *   FILE 136
//*           IOPL          MACRO TO GENERATE TSO IOPL BLOCK        *   FILE 136
//*           JULGREG       JULIAN/GREGORIAN CONVERSION PROGRAM -   *   FILE 136
//*                         CALLED MY HMDCHRON                      *   FILE 136
//*           LDROP         MACRO TO GENERATE DROP STATEMENT        *   FILE 136
//*           LEAVE         MACRO FOR EXIT FROM PROGRAM (RESTORE    *   FILE 136
//*                         REGS, ETC..)                            *   FILE 136
//*           LSPACE        TSO/E COMMAND TO DISPLAY AVAILABLE      *   FILE 136
//*                         SPACE ON VOLUMES                        *   FILE 136
//*           LSPHELP       HELP TEXT FOR THE LSPACE COMMAND        *   FILE 136
//*           LUSE          MACRO TO GENERATE USING STATEMENT       *   FILE 136
//*           NEWVOL        PROGRAM TO CONVERT 3420-->3480 VIA      *   FILE 136
//*                         FATS/FATAR IN CA-1                      *   FILE 136
//*           PDFINIT       TSO/E COMMAND TO INITIALIZE PROFILE FOR *   FILE 136
//*                         ISPF/PDF                                *   FILE 136
//*           PPL           MACRO TO GENERATE TSO PPL BLOCK         *   FILE 136
//*           REGS          MACRO TO GENERATE REGISTER EQUATES      *   FILE 136
//*           SETUSER       INSERT ACF2 LOGONID AND OTHER FIELDS    *   FILE 136
//*                         FOR TSO IN BATCH                        *   FILE 136
//*           TAPESCAN      TAPE SCANNING PROGRAM - UPDATED FOR     *   FILE 136
//*                         3480 DRIVES                             *   FILE 136
//*           TAPESDOC      DOCUMENTATION FOR THE TAPESCAN PROGRAM  *   FILE 136
//*                         (SOMEWHAT OLD)                          *   FILE 136
//*           TSOENTER      MACRO FOR ENTRY TO TSO COMMANDS         *   FILE 136
//*           TSOLEAVE      MACRO FOR EXITING TSO COMMANDS          *   FILE 136
//*           WRU           TSO/E COMMAND TO DISPLAY USER IDENTITY  *   FILE 136
//*           XABSM         MACRO TO SWITCH BETWEEN 31-BIT AND      *   FILE 136
//*                         24-BIT MODES                            *   FILE 136
//*                                                                 *   FILE 136
//*           =============================================         *   FILE 136
//*                                                                 *   FILE 136
//*           NONE OF THE PROGRAMS, ROUTINES, AND MACROS IN THIS    *   FILE 136
//*           DATASET ARE GUARANTEED TO WORK OR BE "SAFE". AS WITH  *   FILE 136
//*           ANY PUBLIC DOMAIN SOFTWARE IT IS THE RESPONSIBILITY   *   FILE 136
//*           OF THE RECEIVING INSTALLATION TO TEST THE SOFTWARE    *   FILE 136
//*           BEFORE RUNNING IT ON THEIR PRODUCTION SYSTEMS. IT MAY *   FILE 136
//*           CRASH YOUR SYSTEM, AND IF IT DOES, AMERICAN PRESIDENT *   FILE 136
//*           SYSTEMS ASSUMES NO RESPONSIBILITY.  INSTALL THIS      *   FILE 136
//*           SOFTWARE ON YOUR SYSTEM AT YOUR OWN RISK.  ALSO,      *   FILE 136
//*           AMERICAN PRESIDENT SYSTEMS DOES NOT GUARANTEE TO FIX  *   FILE 136
//*           ANY OF THESE PROGRAMS OR UPGRADE THEM WHEN THEY       *   FILE 136
//*           BECOME OBSOLETE. AMERICAN PRESIDENT SYSTEMS MAY       *   FILE 136
//*           PERIODICALLY PUT UPDATED VERSION OF THESE AND OTHER   *   FILE 136
//*           PROGRAMS ON THE CBT TAPE, BUT THEY ARE UNDER NO       *   FILE 136
//*           OBLIGATION TO DO SO.  MANY OF THESE PROGRAMS HAVE RUN *   FILE 136
//*           ON OUR SYSTEM, BUT THAT IS NOT A GURARANTEE THEY WILL *   FILE 136
//*           RUN ON YOUR SYSTEM. CAVEAT EMPTOR.                    *   FILE 136
//*                                                                 *   FILE 136
//*           NOTE ALSO, THAT THE SAME RESTRICTIONS ON              *   FILE 136
//*           RESPONSIBILITY FOR OUR INSTALLATION (AMERICAN         *   FILE 136
//*           PRESIDENT SYSTEMS) HOLD TRUE FOR HOWARD DEAN.  I      *   FILE 136
//*           WILL, HOWEVER, ACCEPT SUGGESTIONS FOR IMPROVEMENTS    *   FILE 136
//*           AND ANSWER QUESTIONS ABOUT THESE PROGRAMS. A PROMPT   *   FILE 136
//*           REPLY, THE CORRECT ANSWER, OR TIMELY IMPROVEMENTS     *   FILE 136
//*           ARE NOT GUARANTEED. IF THERE ARE MISSING PARTS TO     *   FILE 136
//*           THESE PROGRAMS, I WILL TRY TO FORWARD THE MACROS OR   *   FILE 136
//*           ROUTINES TO ARNIE AT CBT, HOWEVER I DO NOT GUARANTEE  *   FILE 136
//*           TO DO THIS IN A TIMELY MANNER.  (YOU CAN'T, HOWARD.   *   FILE 136
//*           YOU'D HAVE TO FORWARD THEM TO ME NOW).  ALSO, JUST    *   FILE 136
//*           BECAUSE THESE ROUTINES ARE ON THE CBT TAPE, I AM NOT  *   FILE 136
//*           AVAILABLE FOR "DEMAND" SUPPORT AND NEITHER IS ARNIE   *   FILE 136
//*           CASINGHINO.  (PLEASE NOTICE THAT I AM NOT SAYING YOU  *   FILE 136
//*           MAY CALL ME EITHER, BUT YOU CAN TRY).  YOU MAY CALL   *   FILE 136
//*           US, BUT WE CANNOT GUARANTEE A CORRECT AND PROMPT      *   FILE 136
//*           ANSWER TO YOUR PROBLEM. AGAIN, YOU ARE ON YOUR OWN!   *   FILE 136
//*           CAVEAT EMPTOR.                                        *   FILE 136
//*                                                                 *   FILE 136
```
