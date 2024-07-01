Debugging Details:
------------------


KEY_VALUES_STRING: 1

    Key  : Analysis.CPU.mSec
    Value: 2733

    Key  : Analysis.Elapsed.mSec
    Value: 6800

    Key  : Analysis.IO.Other.Mb
    Value: 3

    Key  : Analysis.IO.Read.Mb
    Value: 0

    Key  : Analysis.IO.Write.Mb
    Value: 26

    Key  : Analysis.Init.CPU.mSec
    Value: 968

    Key  : Analysis.Init.Elapsed.mSec
    Value: 43344

    Key  : Analysis.Memory.CommitPeak.Mb
    Value: 92

    Key  : Bugcheck.Code.LegacyAPI
    Value: 0x1a

    Key  : Bugcheck.Code.TargetModel
    Value: 0x1a

    Key  : Failure.Bucket
    Value: MEMORY_CORRUPTION_ONE_BIT

    Key  : Failure.Hash
    Value: {e3faf315-c3d0-81db-819a-6c43d23c63a7}

    Key  : Hypervisor.Enlightenments.Value
    Value: 68669340

    Key  : Hypervisor.Enlightenments.ValueHex
    Value: 417cf9c

    Key  : Hypervisor.Flags.AnyHypervisorPresent
    Value: 1

    Key  : Hypervisor.Flags.ApicEnlightened
    Value: 1

    Key  : Hypervisor.Flags.ApicVirtualizationAvailable
    Value: 0

    Key  : Hypervisor.Flags.AsyncMemoryHint
    Value: 0

    Key  : Hypervisor.Flags.CoreSchedulerRequested
    Value: 0

    Key  : Hypervisor.Flags.CpuManager
    Value: 1

    Key  : Hypervisor.Flags.DeprecateAutoEoi
    Value: 0

    Key  : Hypervisor.Flags.DynamicCpuDisabled
    Value: 1

    Key  : Hypervisor.Flags.Epf
    Value: 0

    Key  : Hypervisor.Flags.ExtendedProcessorMasks
    Value: 1

    Key  : Hypervisor.Flags.HardwareMbecAvailable
    Value: 0

    Key  : Hypervisor.Flags.MaxBankNumber
    Value: 0

    Key  : Hypervisor.Flags.MemoryZeroingControl
    Value: 0

    Key  : Hypervisor.Flags.NoExtendedRangeFlush
    Value: 0

    Key  : Hypervisor.Flags.NoNonArchCoreSharing
    Value: 1

    Key  : Hypervisor.Flags.Phase0InitDone
    Value: 1

    Key  : Hypervisor.Flags.PowerSchedulerQos
    Value: 0

    Key  : Hypervisor.Flags.RootScheduler
    Value: 0

    Key  : Hypervisor.Flags.SynicAvailable
    Value: 1

    Key  : Hypervisor.Flags.UseQpcBias
    Value: 0

    Key  : Hypervisor.Flags.Value
    Value: 4722927

    Key  : Hypervisor.Flags.ValueHex
    Value: 4810ef

    Key  : Hypervisor.Flags.VpAssistPage
    Value: 1

    Key  : Hypervisor.Flags.VsmAvailable
    Value: 1

    Key  : Hypervisor.RootFlags.AccessStats
    Value: 1

    Key  : Hypervisor.RootFlags.CrashdumpEnlightened
    Value: 1

    Key  : Hypervisor.RootFlags.CreateVirtualProcessor
    Value: 1

    Key  : Hypervisor.RootFlags.DisableHyperthreading
    Value: 0

    Key  : Hypervisor.RootFlags.HostTimelineSync
    Value: 1

    Key  : Hypervisor.RootFlags.HypervisorDebuggingEnabled
    Value: 0

    Key  : Hypervisor.RootFlags.IsHyperV
    Value: 1

    Key  : Hypervisor.RootFlags.LivedumpEnlightened
    Value: 1

    Key  : Hypervisor.RootFlags.MapDeviceInterrupt
    Value: 1

    Key  : Hypervisor.RootFlags.MceEnlightened
    Value: 1

    Key  : Hypervisor.RootFlags.Nested
    Value: 0

    Key  : Hypervisor.RootFlags.StartLogicalProcessor
    Value: 1

    Key  : Hypervisor.RootFlags.Value
    Value: 1015

    Key  : Hypervisor.RootFlags.ValueHex
    Value: 3f7

    Key  : MemoryManagement.PFN
    Value: 200000000

    Key  : WER.OS.Branch
    Value: vb_release

    Key  : WER.OS.Version
    Value: 10.0.19041.1


BUGCHECK_CODE:  1a

BUGCHECK_P1: 41792

BUGCHECK_P2: ffffde0111510468

BUGCHECK_P3: 200000000000

BUGCHECK_P4: 0

FILE_IN_CAB:  070124-14140-01.dmp

MEMORY_CORRUPTOR:  ONE_BIT

BLACKBOXBSD: 1 (!blackboxbsd)


BLACKBOXNTFS: 1 (!blackboxntfs)


BLACKBOXPNP: 1 (!blackboxpnp)


BLACKBOXWINLOGON: 1

CUSTOMER_CRASH_COUNT:  1

PROCESS_NAME:  svchost.exe

STACK_TEXT:  
ffff9685`43b1e338 fffff807`3a882b6a     : 00000000`0000001a 00000000`00041792 ffffde01`11510468 00002000`00000000 : nt!KeBugCheckEx
ffff9685`43b1e340 fffff807`3a88139f     : ffff9a09`3834d740 00000000`00000000 ffffde01`00000002 00000000`00000000 : nt!MiDeleteVa+0x153a
ffff9685`43b1e440 fffff807`3a82b108     : 00000000`00000001 ffff9a09`00000000 ffff9a09`3834d590 ffff9a09`383b20c0 : nt!MiDeletePagablePteRange+0x48f
ffff9685`43b1e750 fffff807`3ac8e7eb     : ffff9a09`00000000 00000000`00000000 ffff9a09`00000000 ffff9a09`3834d0c0 : nt!MiDeleteVad+0x378
ffff9685`43b1e850 fffff807`3ac2fca3     : ffff9a09`3d31a020 ffff9a09`3d31a020 ffff9a09`3d31a2f0 ffff9a09`3834d0c0 : nt!MiCleanVad+0x43
ffff9685`43b1e880 fffff807`3ad12e78     : ffffffff`00000000 ffffffff`ffffffff 00000000`00000001 ffff9a09`3834d0c0 : nt!MmCleanProcessAddressSpace+0x137
ffff9685`43b1e900 fffff807`3ac8a08e     : ffff9a09`3834d0c0 ffffcc81`da2240a0 00000000`00000000 00000000`00000000 : nt!PspRundownSingleProcess+0x20c
ffff9685`43b1e990 fffff807`3acbf15e     : ffff9a09`00000000 00000000`00000001 00000222`9ce062a0 000000c1`1a2d5000 : nt!PspExitThread+0x5f6
ffff9685`43b1ea90 fffff807`3aa11b08     : ffff9a09`3834d0c0 ffff9a09`383b20c0 ffff9685`43b1eb80 ffff9a09`3834d0c0 : nt!NtTerminateProcess+0xde
ffff9685`43b1eb00 00007ffa`db88dae4     : 00000000`00000000 00000000`00000000 00000000`00000000 00000000`00000000 : nt!KiSystemServiceCopyEnd+0x28
000000c1`1a1ef918 00000000`00000000     : 00000000`00000000 00000000`00000000 00000000`00000000 00000000`00000000 : 0x00007ffa`db88dae4


MODULE_NAME: hardware

IMAGE_NAME:  memory_corruption

STACK_COMMAND:  .cxr; .ecxr ; kb

FAILURE_BUCKET_ID:  MEMORY_CORRUPTION_ONE_BIT

OS_VERSION:  10.0.19041.1

BUILDLAB_STR:  vb_release

OSPLATFORM_TYPE:  x64

OSNAME:  Windows 10

FAILURE_ID_HASH:  {e3faf315-c3d0-81db-819a-6c43d23c63a7}

Followup:     MachineOwner
---------
