# Day03
## Part 1
``` PowerShell
$puzzleInpt = 
@"
QJRBMDMtRDCtJzBtJMfjNjhwvmNDvwjLVVgh
TPSNNPZGTjgmSmvfjL
bPlpZZbpsTlTsWprpGFCJtRtzMNdMMBBcWnJQB
tppvbQBhpQQdrzMMcLwhMc
gZnWRccRNgFGRGRFRNNgZgJMddddLLLMCPqwLCNPwqPJ
nRRmFSnWmlgZlTlTllSlSWWWTsfvfDQpBfBcpQvpVQpTfQQf
lRlsVFgTlMgRNsSNTlFgmbWnMPppPnMqWZMWPPWW
fDjgBJdCfCHHBnfLWpqnmnpZmf
GjQHHcdvJHQBHSSNsFQFslwwRg
NPwDLDHNwjLLHWjbdSbDfJJQTZsZDS
BcFBcvgFvghnFLrBpvrgcgrJSZJpQdfSTZbCsSdfZZfbCf
VrngVFRmrVWHLGVMlL
SNBBBDlfZDLqNGmgFjjmBsQgCFtF
VPPVbhpbhMhRhncnScRncbrQtCgQQFmjjjsgtRtQHmFQ
nhWcPJVhpbvMvwvwllvSlGlD
wNlNNqtqHHHPhqCz
MMMMcQSWSpQCWFnRRPchLVvPLLzhmhLzhh
CrgRSWrnrQpppRQrCTnRTRtGtBDBfbNBllbTJlZtfNBN
QNbbNrnNnCwHmNPQmzqQNPsCCfBFFGtsBBddBDtCJDJd
gvVgpZWgTWvRvlvLPDDJjGBfdsdpDDJGdd
ZRMWWRMVgRZghTggPSMZzQwwnqwmnzhNnNwHcQHm
VmPHzBmpmQHbVHSpNHBVQCtRPPCPvFFMqqntZCZqMR
dWlDcfcfcjcfDWjlsZfjJhdGvFLGnLsLqsRnvRvRGGRttC
wfJhZTllcfdZdfjJfjdmQzHVSzHzgHQTpHpmpV
qNnqmzmCBfvmDvBm
HcdhtQdttbbhtVcrVVDMfZvdMBTqsWZMBsWZ
HQGtctRblwqpNwRN
SBtBLBMZzPDDNFFDQnVVVnnDmf
dgCjblRdgRvrbwjJGzQQQzwJVJ
WpWbCWWvlgrcCHdvvCdvWbSLZzhhZhtLBPPStSPhMSpM
PlPnGGGzCqqlrqTRsbTmFRWgDPmR
wwpLtjwpzjDwFWRsWTWW
NZtJjHNNhHfnCBcJMBlCSz
wSrwggPrhJhCdddw
tLMNvMTFhDZdhTBh
LtMvFttGbNcWRsLFLsccRRgfnSrPjPnfljSfPWlnPhrS
TSZlwZSSccSHZLHVcllSvmDLmJhjDDffJmGjQjgQQJ
sdBdzsNnBMBstNNMFhNPNbPzgGfDgJrtrfjCjDrCfJmmDQJf
BnnBznRsFRFBsspzzbZpSTqVTpHVhpTvlqVW
VtVjjhdFmCCfhRRzzSDbDzpmgzmvgb
CHJqrswsWvbvJbpD
CqCPcZHGHTcsCBQsBrTGHMFnLVQjMjLVVhdhnFQVRL
tvlPSrlNNvtglTtPccldQdhbQbZdcqqZ
mRmBGHWmDFRsZqHrfbdhqhZZ
jjMGjWrJpttNjtgg
HPtCMJNjvJLMDZRdBgLSBSfsWBgG
VmnrhwwqhbbzrwnDrqpdWBgfdSdfBGgffGWRdh
qmnTFbVnpqVzpnvlDFJZDClNZPZN
NNRFQfzbNWhLHTVh
dGjptnrPqgvqjccvndnnPPhlHrVVTHLWMHlwmrlHMmVTWm
tDggGnPqDcPPpPpddjGhggtJCCSssfJbQsDfbZsbsbRZFQ
bqZWhbvvvqfvhqvQCChhZlllGwlwGjNRrNGrwGwNRQ
PmspSscJVJStzSVzWJlgwlwNlGRLDGrPgNwN
pdHmWMVStWJWFBBCCbMhCfbC
wtwbctGLwGWhGwfWwhNrnLrlrQFNmPNNVrrl
CSdqZRsMStdJMMSZqPnFmVqPQlnjNjqj
TMtsTBSSRZBCJStMJSZTHtfvpgvzzWwhbpwhggbzHpbW
HncMbCwCncHlcbMDMnMFGsNsJVFJGchVTTcmcG
RRfBRNjRLLJTLTThsq
zpBRjWRrRvBpNtRWrgwbrwQPDPMDwCnn
TDcPLTVRjntFwDwDnb
SJJhffHqHZZgHGSFFbdrGTGnGv
NQHWZgJQHNHgHQhlLLLBjpRTjLjMNNLM
sMNnNRNrlGlsZBrGsrFQpclWlWLfpWjtzTfDtpzj
gvhPgwTgdSHtHDtpDPLp
gwhSwdvTSTbSgRrZNrrNFFNBGb
rtZnDHJrrDtGtGHvGHDWfdfwCjcBhjBCffwwLv
lzVlzsTRsmzVNTspVsMMsmwCLcmjmcdbBBChwfBbCW
sVTMpTpppsVMsPRPVzMNFqMFwZtQrHZDGqgHZrSQQrQQJDGn
wGQQMMQvCTPPQnHPBS
FsWdJddszWrrRRJRTmRmpppRHBNPBppNHp
rWdFWlFJzbzzMTwcvvMbGMgc
WTnnTpqSnCLmjGgSgjztgg
rQRHQvbNLwrgtGtrmDglJt
PwHRNvQPsvHvPTTpLTcCLVnq
qTsqJDJHjjfMCSDj
RnGGNFGznzGVnBCWmfSMSLwWRwSj
NnBbVQFVCClctHQc
BHzmfDHfJLGcQBGgQLDcstNttlZgdlltldshgZZg
PwPPSJwPvSNZlvSl
CJwwjnJFFnWRMcMzcHMHRzGL
rmZpvcZcqccsqmqzzzcBRLBZbBBRLBlRGVdfZR
PwjFggwMDgNFwPgTwNFgtFJjfGLhBLsGRGbfBfBLbbTVLbdf
DWJwgDWMJJDWCCNHmrnscmqqcnpWSQ
bsRlVgMhtzHvhRvpzcLSZcTWLGzTTrGc
QJnDjmqjJdmDqqrGWWsZsZTc
nQPsnwCJdBDJDDJvhHhpMRCVlhlgRV
NBNwMCtNgqCHClHClq
JpQmFrQQfHfWjJTfLTjfLRRFRvnvhvnDGDcRcvVGGV
HTzzpzzdHgbBZZtdMB
SWcVvBFBVBjShWhGQtZnHFDHRGGQsR
pMZpmmJPbwbTTQttrDrRrttT
mZflqdlbMVcNjdWLSj
tvjdccdbLjhvhlcjRMvRTCQJmBPBCFRG
qgnqZfHpZDVnCpZzZJQFQBgmmPFJBmRQJQ
SHDZDDzpNVpfsNsHqpDSjLwCbbWLChwtwjtCWc
FsWTbcwmGfFFFrpl
LMhzdfqjLdHQQnSvldGvnS
VZjVNzfNLtjzDMhVDNtqDqwJwRmmmZJgmgcbWgRRwCbJ
ZJbPwwfJcGlwCrrZrMMddMMMtt
pTNvvSSHmmnbpFRp
SLSjSLDSQNLHNDbJbcfJclBzjGsz
WSQCWQWstCWCCgNNsDCZMZDBjjlLPnHMMLPrHlcrcLHHTjTh
bVFJFwfdRFFgjTPgnc
GmzRRqvRddbdRRdfJRJfsqsSSsZDsDBQZtCSgpgt
FPjprPpPCCFpFPHWsWvqnnllQsdLQMMlLtslLQMc
wmzJgzRSRRJghBbwGBBSbtGfLfGlcNnlltdddQtrMd
zDmRBmwDrpVFDTVDVp
FPGqjsZGlDJmzsHcTcTMMs
SQNLSvdbvVbrSbHcftGcrpHGfMmf
CNNGSCCdSCZqjqljZF
GvqpqrpqdqdsdGshSMhhRsSMhhlSlJ
DLCzzjzBwCbQWtQlRRFRRJFptfffgM
WzpLbLDbBcLPjWQWDBzzmnvNndHNqZqZNZNvcrNT
scHCGfWHsvWHVfGsggHfgvVcSLwLLPRwwDLPLllRPDzlPr
tbjqqNNTlPDTTSrD
QntmNbNnnddqJqqbFJHZWWHWJWvZHGVJsSsp
WZjpjwwGBGZQsqBLBHLHSRLP
mJhtdfVtDVJtvVLSmNRSccPPPlNHcH
JJLCFDhLCfVGGwbGGCwrGC
nBnsGSCrptmsLWGhWRvVRJVJ
rllMZZbcWWLJvhTl
MHwzczHwwHqZcdzMdbqSmwsssmtNCrBmtrnQNB
LzwrZNrNzBMrJBzJsfqqntMlVlSfhnhb
HTDPWDHPTgGHWTGcPFRgFpPPtfqmsfqlccmlSmnblbshqnmm
jWGgpRGPFRHjzdBBsrBJvj
hjNghjlwqjzGhwhGwLrMMrsMdsMfczPfsr
ZJQSFZFZpCTQSZHTTFbcWWPbWsWrdLVmrMWMfr
tttHSCpFQBQQpJZSJLgBNNDhqhBqvBvvRq
hLLJJJLcLPLfLwcJDchfhpSmqGbmdQGmGSdbqdbmqGGGdG
zgCCVVvVCNVssdbqmtMWvbnndD
rCCZZCVTjVZNzFZJBlflBLccDhBFFB
wwPPHfCMHQsrcwPbMPMcvQFJvqWgFTZgDFJltgZt
jRBVLhpNqpBmRhhRdNJZJgWTBBtgZWltZJJJ
mSjndhSzphjLRVqmhphNShrGMGrcbGbnGCHGwrwGfbbG
PVBRhBdlwRtRhRBwtBlVzDcGpVcZnggGzGMMsg
fFFWQqbFbLWCWvvFbTjjGnsZMfgsZcZzSZGMpSgD
QJTCCLFFLjFqFbHTbbltmhBNwwcNmthNhlHr
qwPJJsJdbPdwJddQCRCgCTMTRGGwMG
cLFcFBZNWWQLSQRfZjpljTGRCgGR
cFvrcNBFJDhzdQzv
zTsVTqDqQNtNwwMVmN
pHpSzPbRrvbRrGzGMwZwlBJmNtclwJpB
SjHRPfRbffPHqzCCCdTsTzqj
jnbMBnPjjjFtBtMjFPRtGfvvfzgWWHMfWHTlGgHH
dCpdqrVrmdpHfTJTCWGJgG
qVdrppqSTddqNwZcDPPPhZRBPBLBRLjF
VbHqLlGQlgjLjjQsNvCZTsNjMtCZvT
SJtttppwwpwBwdPvsvCvBZrvNrTrvM
JDnWJpDSSpmSwmpPzSwznhDlqGqqtqqHGHLlhblGbR
RqRJJVMPdRVVpqMdFwmvnSMwZcfCGfDSZc
CssQgjssvZvjffmS
zNlbbWTBLWCbCPPFPbVH
nvQsHSsGvNvnQghTRMrrjpjM
ttlLDlzPtGDcRRtpZTFjtgMj
PBLBwPPDzzLwblzffzLlVHHsCCHqsfvCCSsGSNWC
jHrTrThrtHgttThgHTtfgTgsmZZmBSZGSGsSGfZBZFFmQs
qCCPdbcCJddbRcsQSGhFzmZqZGmq
VVNNdVvclDcPbMWMwnnlwhphjp
ZdBgJqFWNNNqnZZNGsBCCCRvrCwCjCssCB
htDPMSPtMPzPTLMzMTMbRRbTbvwRCjfRfsbWWs
LhMmtMDWmHlpppplJZJgNd
mhtsjtbChcpLqmpmzL
DPlPprrfBrpGHHVGNVHRqcNvvLLqLcvJzzTvLc
VFfVPrrBQFPlDDwDwBpBtSgQjnghMhCdbSnnhtMM
DPDMpbsHPDPNtdtrgMtdnQ
WShWlSCJVlzccSBvBvhVZZWlgTNTrNrrQTjQjjjjgDSgSdNt
cvmCDvCJCcsRbmpFmqms
sSfFssmLnLwPtrrmttsFbDvWgCvddVgfgWdRDWlChD
nnGnHBzqHjqBJGChlRClhvghJWDd
jNzNcczMcGntPMwwSsSr
GGPCThCCvCTVWBCBGMVMsTgZJsrZtHNNtrsHJrgH
zjRwcwwfvSjmwznfzQSHDJtgrNrRNrLDsRrHtD
fjvzmcfSlSznwcnmnSQnhdlhWBpGpdBqhGhqhVPd
sHGGqpRqfNRVbDDtVwwzWf
CCLQZllTQLTcSShTQvjhQLnnWrDzVpwtDDwVDnczwMwM
vggZLZTldlhpCTlZlZCRRPNRmqdmGBHPFqsGqN
wwFDFLMDjjCNgNwNlwwgvR
frPbSJMSSPBqrfppSqrBZqMQhHlmNsRZmmslvghsmhsgggtZ
TPSPfBQrdJSfTTqSbbBfTfdcGWjFWWFDWnGMjLjGVFCj
LZRZbHtqnVztHTTTjMBQjQHH
rJcDGpwwgDwCCWFGSFMSffVWfF
cNNNgvhNglDnhdzsbLbmVs
RwmrGVPmNLzdmVpmrVtHDjjgDHHRqjFtngFt
CBlWhQWlTWshsblFGntjHtGbHG
WsTSGZSTQZZJpPNdzSrzwvpr
CVsggSgdwSwghVSTCgVZjJlRvlQNJHJGZVvjvj
qrrnzrrpDFMzbDbbzrMbBcNjRBHHQHGRRllHHPBNBljl
rnFppcpWcqnWMLDNsggSmWmsWfggdg
wjQzPjJcplwmDDBL
vghWhhnfWqzhftWtfnbFBmnGDnLGDbDmmC
zZNvZrNsWfgVftNZhQcSdPHPTcPHQQTTJV
WjvPVbWnbbFvjfLlcplQvLQvCwCl
sJhmrrTRTDDJHhhsmJhmrNDdQwLQQlHllHwwLpCLclBBlcPC
RJTRDdmPmmzNTDhnWtzMfMWtqjqqWM
vvpjqtllDMlHDtDBsPSSfBJFlSffNS
gwTmJrTcJWrNSmsNBBPfmf
VzzJzgTnddzWrwngnWqbHqbtLqjqvpvqhbMd
TlpzwGZGGFmZJdPpRtpHPrpcPs
CMJCMgQjMQvrfMHtMfHv
DjnNjCBqCCNnWWgDBQQDnCZwFJwmwwTznmFVwFmzTJJm
CcDPppDCFdDrFcFsMsdlLVjjLsMHvM
fqSmmtNGqLNffhHHbsMsbjbjNjbv
SthSGmLnmfwfWGWhSQGSQRnGpDpJPCDJrBPTcPrDwPzFcpFT
FdqjDtPWzqPdnPPtPFbssllqLJlqNppsJGppLp
TwfrcvwRgvfTBWRgBssJhspHfffJHlHNGh
MMZCQrrRBwQCCZMQwcTMwPztnFZSDWVWPttPSZzdzd
prHlrpJbdccllrrPbFdrgPzZfZhZVhRZVScNRNWtSZjWRW
LmwCCnvqwGCLMnsWtGRZWVfbfbftRW
bwnvBnLBvbsBvszHzpgBlPzHHlzg
grSJNTSgBHgpqhvCGbbZddGCGbbT
nDLMssQMRLwMtMWRWCZdQfqjfGvZQfCjCc
PqsDWPMLnwlRllJzghmgmSNhpgrl
TQGcWQBDnSzzsBSL
mJJlqJwVJdbSrhlrlhhsLL
JPtwMtdPbJbVqVNpPtmbpwZcQDFFcCccFjCQjpQWSWZg
JfbfpZJmzffmpZnZZwsrwDFvwHPP
RDdQtWTWQQSTGNRhsFsjnvjwrhPjtH
QccddTVQQldcGGRdGlgmVmBzfVpDmbgggmpL
HVnhVcHvpVFWDpmP
QswNZblTTwmqlntDPdqD
sGZzNwsGNThhMrhBBhzn
fQllBlVQncgwLlfWwWDvppZZggZqGpZgpGdvGG
shPTRsFbNFJmvqpGjrpvPDdr
RNFDtRRRssRTStRmTlnzwSVQlVVWfWzcQc
WmCpPCWTjQPCWWSjSTmrqRLGDRFGrTFDRFDLDD
gJnVcnVzdfnZgchvrslMDZGlRRDZLR
fdHhfncwfbfzJbnJzJfcczhhSmLCCNBjSpjmpjHjBQjpmpNW
BDvDPGRwRvCmLssGLmsL
frRjjlldrqtNspLWpqFcCmzm
ndSnVNtllldrdfSjfNvgVRHBwbbVMRbVPJgH
PpgjhpVLghPZhSgZVVzzcJWccPNCrcJzrFsJ
BdBNNMqMdfDnDNTFHHJCqHrJHzrFzF
wfMNtMndlBTlmTBndRpgghhjZRjvSZVjRw
ZQnQMWMcjHDHrWNF
TvtCvvBVgdRdmvBVNzDHlGFjFHjfRfDD
dvtCCbdJmhvhhhhbhVBPMwqZswnZqZjjMccsZJ
DDMzRBBSzRDTMQRZsbvssCbhZtCDtP
dLmwNplnmmwjGvPVCRtVVvVd
NNmjLmqWJjFRwFSrgcrSHBzcTz
TwTwTMBWcWBJJBtTWHddCmfgzlCzClsvmfsM
PPLDnNqPRLQNVnGNVsDQnNmzdhvdddlvdlqgqmdlrfvv
SQQsjPPLGLbDSnGLLNnWTFZJHbcpFctHZpwJWB
FzMltgtMzFpZtmzdjPpnvRTQTvRWTDfnnTlvwW
JcbVcBrqLCVJHJSNCcZVqVqqTRQRWWfNsTfTvDfsWvwTsnwv
rcZqVJVhmhgPmhmd
ttvSnlWvWWgcScMDsHHMPMjPmH
pzLGLfNRpJsvmmfvMDfs
GhpzRqqpZppNrhvFgwSlWnnBFn
sbQcDJQJJDbQhwchSctVnVnqTMvMWSqTMPSMlP
jtjCtNRLNCRgRnlTPPWg
pzpHdLtFNdJbDhJHsQhs
pSqnfqDnWPHNPCCHCp
GdJZQdgZbBvgQLcCZZCCZlPLRH
PzBgQggbvBthtMdMvbzvVfFfzTWqDmWDqzqWrfff
nnJdrfgfrdMCMdgrqMnWdgwNTTTzFhPSSHfSHhllzjzNFT
vBRvmvGZsLZZsHFNFFzTNPzb
LZVRmcDRvpQLmvvVGDGmpntJJwCWCnCPJwgJDrPDqM
QddMvdzlVfvdSQmGhmwLbGbmzbns
JtCCWqqZDsLpGhbGjD
FNrhqCTWMSRSrQQg
ZsBZJFsZSmmJsJSmrJrJrvsrdGdCQGQphMGwRMGQRGdbBChM
FlgfqNNNWnNnHfVnnHdbGwpwGWQhGdRMMdRM
LFnggHlDqDLvjDmZPcPmvP
CRHJWfvJvrQfrCsDlGGBszQBjjGB
LmPHVnMmpLlPssBPlDtd
MmMSZmVnncMFcmSVHvfSrffCwSvfbHWv
wsrJrpdJLsMCZDWL
BbLtGGbNmLQggqgQQtGgMmDCTnWZCZWZTmMmCZnT
qNBGNNgQcbbtGbbFBLVjfcfwHvrHHJHJcr
pCZCpdjBljhjBlpVccCpbDDwRWDsLhLbwDsDwsDw
HNgFSSNvSmdqwsFLFWLGttbw
gMMndNrzNHnzJZVlMCMCTcpc
CfsFNszCrrGzrsggsPfPVNVlqTdSjSqMTdSVTdLL
vRhcHllwJDmnJmDMMdhqSqpVMhdjdp
cvHRvwQBPZZlrQgz
TsFhCtQtQsBBLtBLPvgz
jjWZZjZSMNlNNjljNnlmjjfJLMBGGLvBdzPQpggJJLQzpg
wjbcmmlnQZmlrTsCFVwshwTr
nRGFnFjcdlwLSHSpNNnBfWHN
TgQvPbCMPRhbMPQvtQPvMCRBSHNQHBrQSNfWqpHHrWNWSf
PCgMbPvTZVDgtPRggtCCbgmmFJJLmcGFLjdmJFcDwJmm
dgWPssfdvQCLPLhL
pMtSMtpSmpMpFSMMFZjQCLbLQZZbVbVhNTLblZ
mpqcpzncfWwhzfRf
vntvVnRCsvpBpMjCpTpj
rQdZfhzczNzWcNLTpWgSvjjjpGpMSB
ZqNDQhfcNchLchQqcDqRHJtHVwnwbtvHsbVs
qtJGQgTrqtqQdQDgbGjPzZHWWzVjslPZlG
vBShwRRvvSRSvFvwLSvfcnfBWmHZHVWWHPzlNPWVWjZsWnWV
cLBFBFhCBLlwpFccFBFftqJDQdgdTDJJCbJgCCdg
wfmsPvPwNfvmfLNFvzzJbRMnllhlnLhRLC
gjtqDDTtjgpJcbnMTzCRnCCWhC
SDqtpGSStVtdqpgBVjBGZmFPJNJmffvfPsHZPZQd
HQMBBWrQQmPBvmBWnvrTnMSsbFfcfwgfCgscsmGgwgcJGg
NzzlJLthtlgswGFcwGst
JqNNRqpzhVRWTSQrrvSQ
mFpDZjvmtPPGvFjmmGTzTcFRbHczHTbzQgRS
fNdqhJsNrnnVNhwNVdrdsVczQCcwCMHSTCHgHCRzHgcM
JlgnNhsqVqNqNpPlvZvDDDGlZZ
"@ -split "`r`n"

$inventory    = [System.Collections.Generic.List[PSCustomObject]]::new()
$priorityhash = New-Object system.collections.hashtable

#region - Hash
$priorityhash.'a'=1
$priorityhash.'b'=2
$priorityhash.'c'=3
$priorityhash.'d'=4
$priorityhash.'e'=5
$priorityhash.'f'=6
$priorityhash.'g'=7
$priorityhash.'h'=8
$priorityhash.'i'=9
$priorityhash.'j'=10
$priorityhash.'k'=11
$priorityhash.'l'=12
$priorityhash.'m'=13
$priorityhash.'n'=14
$priorityhash.'o'=15
$priorityhash.'p'=16
$priorityhash.'q'=17
$priorityhash.'r'=18
$priorityhash.'s'=19
$priorityhash.'t'=20
$priorityhash.'u'=21
$priorityhash.'v'=22
$priorityhash.'w'=23
$priorityhash.'x'=24
$priorityhash.'y'=25
$priorityhash.'z'=26
$priorityhash.'A'=27
$priorityhash.'B'=28
$priorityhash.'C'=29
$priorityhash.'D'=30
$priorityhash.'E'=31
$priorityhash.'F'=32
$priorityhash.'G'=33
$priorityhash.'H'=34
$priorityhash.'I'=35
$priorityhash.'J'=36
$priorityhash.'K'=37
$priorityhash.'L'=38
$priorityhash.'M'=39
$priorityhash.'N'=40
$priorityhash.'O'=41
$priorityhash.'P'=42
$priorityhash.'Q'=43
$priorityhash.'R'=44
$priorityhash.'S'=45
$priorityhash.'T'=46
$priorityhash.'U'=47
$priorityhash.'V'=48
$priorityhash.'W'=49
$priorityhash.'X'=50
$priorityhash.'Y'=51
$priorityhash.'Z'=52
#endregion

foreach($item in $puzzleInpt){
    $divider = $item.Length / 2
    $comp1   = ( $item.Substring($divider) ).toCharArray()
    $comp2   = ( $item.Substring(0,$divider) ).toCharArray()

    $findCommon = 
    foreach($char1 in $comp1){
        foreach($char2 in $comp2){
            if( $char1 -ceq $char2){
                $char1
            }
        }
    }

    $common = $findCommon | select -Unique
    $inventory.add(
        $priorityhash["$common"]
    )
    
}

($inventory | measure -sum).sum
```
## Part 2
``` PowerShell
$puzzleInput = 
@"
QJRBMDMtRDCtJzBtJMfjNjhwvmNDvwjLVVgh
TPSNNPZGTjgmSmvfjL
bPlpZZbpsTlTsWprpGFCJtRtzMNdMMBBcWnJQB
tppvbQBhpQQdrzMMcLwhMc
gZnWRccRNgFGRGRFRNNgZgJMddddLLLMCPqwLCNPwqPJ
nRRmFSnWmlgZlTlTllSlSWWWTsfvfDQpBfBcpQvpVQpTfQQf
lRlsVFgTlMgRNsSNTlFgmbWnMPppPnMqWZMWPPWW
fDjgBJdCfCHHBnfLWpqnmnpZmf
GjQHHcdvJHQBHSSNsFQFslwwRg
NPwDLDHNwjLLHWjbdSbDfJJQTZsZDS
BcFBcvgFvghnFLrBpvrgcgrJSZJpQdfSTZbCsSdfZZfbCf
VrngVFRmrVWHLGVMlL
SNBBBDlfZDLqNGmgFjjmBsQgCFtF
VPPVbhpbhMhRhncnScRncbrQtCgQQFmjjjsgtRtQHmFQ
nhWcPJVhpbvMvwvwllvSlGlD
wNlNNqtqHHHPhqCz
MMMMcQSWSpQCWFnRRPchLVvPLLzhmhLzhh
CrgRSWrnrQpppRQrCTnRTRtGtBDBfbNBllbTJlZtfNBN
QNbbNrnNnCwHmNPQmzqQNPsCCfBFFGtsBBddBDtCJDJd
gvVgpZWgTWvRvlvLPDDJjGBfdsdpDDJGdd
ZRMWWRMVgRZghTggPSMZzQwwnqwmnzhNnNwHcQHm
VmPHzBmpmQHbVHSpNHBVQCtRPPCPvFFMqqntZCZqMR
dWlDcfcfcjcfDWjlsZfjJhdGvFLGnLsLqsRnvRvRGGRttC
wfJhZTllcfdZdfjJfjdmQzHVSzHzgHQTpHpmpV
qNnqmzmCBfvmDvBm
HcdhtQdttbbhtVcrVVDMfZvdMBTqsWZMBsWZ
HQGtctRblwqpNwRN
SBtBLBMZzPDDNFFDQnVVVnnDmf
dgCjblRdgRvrbwjJGzQQQzwJVJ
WpWbCWWvlgrcCHdvvCdvWbSLZzhhZhtLBPPStSPhMSpM
PlPnGGGzCqqlrqTRsbTmFRWgDPmR
wwpLtjwpzjDwFWRsWTWW
NZtJjHNNhHfnCBcJMBlCSz
wSrwggPrhJhCdddw
tLMNvMTFhDZdhTBh
LtMvFttGbNcWRsLFLsccRRgfnSrPjPnfljSfPWlnPhrS
TSZlwZSSccSHZLHVcllSvmDLmJhjDDffJmGjQjgQQJ
sdBdzsNnBMBstNNMFhNPNbPzgGfDgJrtrfjCjDrCfJmmDQJf
BnnBznRsFRFBsspzzbZpSTqVTpHVhpTvlqVW
VtVjjhdFmCCfhRRzzSDbDzpmgzmvgb
CHJqrswsWvbvJbpD
CqCPcZHGHTcsCBQsBrTGHMFnLVQjMjLVVhdhnFQVRL
tvlPSrlNNvtglTtPccldQdhbQbZdcqqZ
mRmBGHWmDFRsZqHrfbdhqhZZ
jjMGjWrJpttNjtgg
HPtCMJNjvJLMDZRdBgLSBSfsWBgG
VmnrhwwqhbbzrwnDrqpdWBgfdSdfBGgffGWRdh
qmnTFbVnpqVzpnvlDFJZDClNZPZN
NNRFQfzbNWhLHTVh
dGjptnrPqgvqjccvndnnPPhlHrVVTHLWMHlwmrlHMmVTWm
tDggGnPqDcPPpPpddjGhggtJCCSssfJbQsDfbZsbsbRZFQ
bqZWhbvvvqfvhqvQCChhZlllGwlwGjNRrNGrwGwNRQ
PmspSscJVJStzSVzWJlgwlwNlGRLDGrPgNwN
pdHmWMVStWJWFBBCCbMhCfbC
wtwbctGLwGWhGwfWwhNrnLrlrQFNmPNNVrrl
CSdqZRsMStdJMMSZqPnFmVqPQlnjNjqj
TMtsTBSSRZBCJStMJSZTHtfvpgvzzWwhbpwhggbzHpbW
HncMbCwCncHlcbMDMnMFGsNsJVFJGchVTTcmcG
RRfBRNjRLLJTLTThsq
zpBRjWRrRvBpNtRWrgwbrwQPDPMDwCnn
TDcPLTVRjntFwDwDnb
SJJhffHqHZZgHGSFFbdrGTGnGv
NQHWZgJQHNHgHQhlLLLBjpRTjLjMNNLM
sMNnNRNrlGlsZBrGsrFQpclWlWLfpWjtzTfDtpzj
gvhPgwTgdSHtHDtpDPLp
gwhSwdvTSTbSgRrZNrrNFFNBGb
rtZnDHJrrDtGtGHvGHDWfdfwCjcBhjBCffwwLv
lzVlzsTRsmzVNTspVsMMsmwCLcmjmcdbBBChwfBbCW
sVTMpTpppsVMsPRPVzMNFqMFwZtQrHZDGqgHZrSQQrQQJDGn
wGQQMMQvCTPPQnHPBS
FsWdJddszWrrRRJRTmRmpppRHBNPBppNHp
rWdFWlFJzbzzMTwcvvMbGMgc
WTnnTpqSnCLmjGgSgjztgg
rQRHQvbNLwrgtGtrmDglJt
PwHRNvQPsvHvPTTpLTcCLVnq
qTsqJDJHjjfMCSDj
RnGGNFGznzGVnBCWmfSMSLwWRwSj
NnBbVQFVCClctHQc
BHzmfDHfJLGcQBGgQLDcstNttlZgdlltldshgZZg
PwPPSJwPvSNZlvSl
CJwwjnJFFnWRMcMzcHMHRzGL
rmZpvcZcqccsqmqzzzcBRLBZbBBRLBlRGVdfZR
PwjFggwMDgNFwPgTwNFgtFJjfGLhBLsGRGbfBfBLbbTVLbdf
DWJwgDWMJJDWCCNHmrnscmqqcnpWSQ
bsRlVgMhtzHvhRvpzcLSZcTWLGzTTrGc
QJnDjmqjJdmDqqrGWWsZsZTc
nQPsnwCJdBDJDDJvhHhpMRCVlhlgRV
NBNwMCtNgqCHClHClq
JpQmFrQQfHfWjJTfLTjfLRRFRvnvhvnDGDcRcvVGGV
HTzzpzzdHgbBZZtdMB
SWcVvBFBVBjShWhGQtZnHFDHRGGQsR
pMZpmmJPbwbTTQttrDrRrttT
mZflqdlbMVcNjdWLSj
tvjdccdbLjhvhlcjRMvRTCQJmBPBCFRG
qgnqZfHpZDVnCpZzZJQFQBgmmPFJBmRQJQ
SHDZDDzpNVpfsNsHqpDSjLwCbbWLChwtwjtCWc
FsWTbcwmGfFFFrpl
LMhzdfqjLdHQQnSvldGvnS
VZjVNzfNLtjzDMhVDNtqDqwJwRmmmZJgmgcbWgRRwCbJ
ZJbPwwfJcGlwCrrZrMMddMMMtt
pTNvvSSHmmnbpFRp
SLSjSLDSQNLHNDbJbcfJclBzjGsz
WSQCWQWstCWCCgNNsDCZMZDBjjlLPnHMMLPrHlcrcLHHTjTh
bVFJFwfdRFFgjTPgnc
GmzRRqvRddbdRRdfJRJfsqsSSsZDsDBQZtCSgpgt
FPjprPpPCCFpFPHWsWvqnnllQsdLQMMlLtslLQMc
wmzJgzRSRRJghBbwGBBSbtGfLfGlcNnlltdddQtrMd
zDmRBmwDrpVFDTVDVp
FPGqjsZGlDJmzsHcTcTMMs
SQNLSvdbvVbrSbHcftGcrpHGfMmf
CNNGSCCdSCZqjqljZF
GvqpqrpqdqdsdGshSMhhRsSMhhlSlJ
DLCzzjzBwCbQWtQlRRFRRJFptfffgM
WzpLbLDbBcLPjWQWDBzzmnvNndHNqZqZNZNvcrNT
scHCGfWHsvWHVfGsggHfgvVcSLwLLPRwwDLPLllRPDzlPr
tbjqqNNTlPDTTSrD
QntmNbNnnddqJqqbFJHZWWHWJWvZHGVJsSsp
WZjpjwwGBGZQsqBLBHLHSRLP
mJhtdfVtDVJtvVLSmNRSccPPPlNHcH
JJLCFDhLCfVGGwbGGCwrGC
nBnsGSCrptmsLWGhWRvVRJVJ
rllMZZbcWWLJvhTl
MHwzczHwwHqZcdzMdbqSmwsssmtNCrBmtrnQNB
LzwrZNrNzBMrJBzJsfqqntMlVlSfhnhb
HTDPWDHPTgGHWTGcPFRgFpPPtfqmsfqlccmlSmnblbshqnmm
jWGgpRGPFRHjzdBBsrBJvj
hjNghjlwqjzGhwhGwLrMMrsMdsMfczPfsr
ZJQSFZFZpCTQSZHTTFbcWWPbWsWrdLVmrMWMfr
tttHSCpFQBQQpJZSJLgBNNDhqhBqvBvvRq
hLLJJJLcLPLfLwcJDchfhpSmqGbmdQGmGSdbqdbmqGGGdG
zgCCVVvVCNVssdbqmtMWvbnndD
rCCZZCVTjVZNzFZJBlflBLccDhBFFB
wwPPHfCMHQsrcwPbMPMcvQFJvqWgFTZgDFJltgZt
jRBVLhpNqpBmRhhRdNJZJgWTBBtgZWltZJJJ
mSjndhSzphjLRVqmhphNShrGMGrcbGbnGCHGwrwGfbbG
PVBRhBdlwRtRhRBwtBlVzDcGpVcZnggGzGMMsg
fFFWQqbFbLWCWvvFbTjjGnsZMfgsZcZzSZGMpSgD
QJTCCLFFLjFqFbHTbbltmhBNwwcNmthNhlHr
qwPJJsJdbPdwJddQCRCgCTMTRGGwMG
cLFcFBZNWWQLSQRfZjpljTGRCgGR
cFvrcNBFJDhzdQzv
zTsVTqDqQNtNwwMVmN
pHpSzPbRrvbRrGzGMwZwlBJmNtclwJpB
SjHRPfRbffPHqzCCCdTsTzqj
jnbMBnPjjjFtBtMjFPRtGfvvfzgWWHMfWHTlGgHH
dCpdqrVrmdpHfTJTCWGJgG
qVdrppqSTddqNwZcDPPPhZRBPBLBRLjF
VbHqLlGQlgjLjjQsNvCZTsNjMtCZvT
SJtttppwwpwBwdPvsvCvBZrvNrTrvM
JDnWJpDSSpmSwmpPzSwznhDlqGqqtqqHGHLlhblGbR
RqRJJVMPdRVVpqMdFwmvnSMwZcfCGfDSZc
CssQgjssvZvjffmS
zNlbbWTBLWCbCPPFPbVH
nvQsHSsGvNvnQghTRMrrjpjM
ttlLDlzPtGDcRRtpZTFjtgMj
PBLBwPPDzzLwblzffzLlVHHsCCHqsfvCCSsGSNWC
jHrTrThrtHgttThgHTtfgTgsmZZmBSZGSGsSGfZBZFFmQs
qCCPdbcCJddbRcsQSGhFzmZqZGmq
VVNNdVvclDcPbMWMwnnlwhphjp
ZdBgJqFWNNNqnZZNGsBCCCRvrCwCjCssCB
htDPMSPtMPzPTLMzMTMbRRbTbvwRCjfRfsbWWs
LhMmtMDWmHlpppplJZJgNd
mhtsjtbChcpLqmpmzL
DPlPprrfBrpGHHVGNVHRqcNvvLLqLcvJzzTvLc
VFfVPrrBQFPlDDwDwBpBtSgQjnghMhCdbSnnhtMM
DPDMpbsHPDPNtdtrgMtdnQ
WShWlSCJVlzccSBvBvhVZZWlgTNTrNrrQTjQjjjjgDSgSdNt
cvmCDvCJCcsRbmpFmqms
sSfFssmLnLwPtrrmttsFbDvWgCvddVgfgWdRDWlChD
nnGnHBzqHjqBJGChlRClhvghJWDd
jNzNcczMcGntPMwwSsSr
GGPCThCCvCTVWBCBGMVMsTgZJsrZtHNNtrsHJrgH
zjRwcwwfvSjmwznfzQSHDJtgrNrRNrLDsRrHtD
fjvzmcfSlSznwcnmnSQnhdlhWBpGpdBqhGhqhVPd
sHGGqpRqfNRVbDDtVwwzWf
CCLQZllTQLTcSShTQvjhQLnnWrDzVpwtDDwVDnczwMwM
vggZLZTldlhpCTlZlZCRRPNRmqdmGBHPFqsGqN
wwFDFLMDjjCNgNwNlwwgvR
frPbSJMSSPBqrfppSqrBZqMQhHlmNsRZmmslvghsmhsgggtZ
TPSPfBQrdJSfTTqSbbBfTfdcGWjFWWFDWnGMjLjGVFCj
LZRZbHtqnVztHTTTjMBQjQHH
rJcDGpwwgDwCCWFGSFMSffVWfF
cNNNgvhNglDnhdzsbLbmVs
RwmrGVPmNLzdmVpmrVtHDjjgDHHRqjFtngFt
CBlWhQWlTWshsblFGntjHtGbHG
WsTSGZSTQZZJpPNdzSrzwvpr
CVsggSgdwSwghVSTCgVZjJlRvlQNJHJGZVvjvj
qrrnzrrpDFMzbDbbzrMbBcNjRBHHQHGRRllHHPBNBljl
rnFppcpWcqnWMLDNsggSmWmsWfggdg
wjQzPjJcplwmDDBL
vghWhhnfWqzhftWtfnbFBmnGDnLGDbDmmC
zZNvZrNsWfgVftNZhQcSdPHPTcPHQQTTJV
WjvPVbWnbbFvjfLlcplQvLQvCwCl
sJhmrrTRTDDJHhhsmJhmrNDdQwLQQlHllHwwLpCLclBBlcPC
RJTRDdmPmmzNTDhnWtzMfMWtqjqqWM
vvpjqtllDMlHDtDBsPSSfBJFlSffNS
gwTmJrTcJWrNSmsNBBPfmf
VzzJzgTnddzWrwngnWqbHqbtLqjqvpvqhbMd
TlpzwGZGGFmZJdPpRtpHPrpcPs
CMJCMgQjMQvrfMHtMfHv
DjnNjCBqCCNnWWgDBQQDnCZwFJwmwwTznmFVwFmzTJJm
CcDPppDCFdDrFcFsMsdlLVjjLsMHvM
fqSmmtNGqLNffhHHbsMsbjbjNjbv
SthSGmLnmfwfWGWhSQGSQRnGpDpJPCDJrBPTcPrDwPzFcpFT
FdqjDtPWzqPdnPPtPFbssllqLJlqNppsJGppLp
TwfrcvwRgvfTBWRgBssJhspHfffJHlHNGh
MMZCQrrRBwQCCZMQwcTMwPztnFZSDWVWPttPSZzdzd
prHlrpJbdccllrrPbFdrgPzZfZhZVhRZVScNRNWtSZjWRW
LmwCCnvqwGCLMnsWtGRZWVfbfbftRW
bwnvBnLBvbsBvszHzpgBlPzHHlzg
grSJNTSgBHgpqhvCGbbZddGCGbbT
nDLMssQMRLwMtMWRWCZdQfqjfGvZQfCjCc
PqsDWPMLnwlRllJzghmgmSNhpgrl
TQGcWQBDnSzzsBSL
mJJlqJwVJdbSrhlrlhhsLL
JPtwMtdPbJbVqVNpPtmbpwZcQDFFcCccFjCQjpQWSWZg
JfbfpZJmzffmpZnZZwsrwDFvwHPP
RDdQtWTWQQSTGNRhsFsjnvjwrhPjtH
QccddTVQQldcGGRdGlgmVmBzfVpDmbgggmpL
HVnhVcHvpVFWDpmP
QswNZblTTwmqlntDPdqD
sGZzNwsGNThhMrhBBhzn
fQllBlVQncgwLlfWwWDvppZZggZqGpZgpGdvGG
shPTRsFbNFJmvqpGjrpvPDdr
RNFDtRRRssRTStRmTlnzwSVQlVVWfWzcQc
WmCpPCWTjQPCWWSjSTmrqRLGDRFGrTFDRFDLDD
gJnVcnVzdfnZgchvrslMDZGlRRDZLR
fdHhfncwfbfzJbnJzJfcczhhSmLCCNBjSpjmpjHjBQjpmpNW
BDvDPGRwRvCmLssGLmsL
frRjjlldrqtNspLWpqFcCmzm
ndSnVNtllldrdfSjfNvgVRHBwbbVMRbVPJgH
PpgjhpVLghPZhSgZVVzzcJWccPNCrcJzrFsJ
BdBNNMqMdfDnDNTFHHJCqHrJHzrFzF
wfMNtMndlBTlmTBndRpgghhjZRjvSZVjRw
ZQnQMWMcjHDHrWNF
TvtCvvBVgdRdmvBVNzDHlGFjFHjfRfDD
dvtCCbdJmhvhhhhbhVBPMwqZswnZqZjjMccsZJ
DDMzRBBSzRDTMQRZsbvssCbhZtCDtP
dLmwNplnmmwjGvPVCRtVVvVd
NNmjLmqWJjFRwFSrgcrSHBzcTz
TwTwTMBWcWBJJBtTWHddCmfgzlCzClsvmfsM
PPLDnNqPRLQNVnGNVsDQnNmzdhvdddlvdlqgqmdlrfvv
SQQsjPPLGLbDSnGLLNnWTFZJHbcpFctHZpwJWB
FzMltgtMzFpZtmzdjPpnvRTQTvRWTDfnnTlvwW
JcbVcBrqLCVJHJSNCcZVqVqqTRQRWWfNsTfTvDfsWvwTsnwv
rcZqVJVhmhgPmhmd
ttvSnlWvWWgcScMDsHHMPMjPmH
pzLGLfNRpJsvmmfvMDfs
GhpzRqqpZppNrhvFgwSlWnnBFn
sbQcDJQJJDbQhwchSctVnVnqTMvMWSqTMPSMlP
jtjCtNRLNCRgRnlTPPWg
pzpHdLtFNdJbDhJHsQhs
pSqnfqDnWPHNPCCHCp
GdJZQdgZbBvgQLcCZZCCZlPLRH
PzBgQggbvBthtMdMvbzvVfFfzTWqDmWDqzqWrfff
nnJdrfgfrdMCMdgrqMnWdgwNTTTzFhPSSHfSHhllzjzNFT
vBRvmvGZsLZZsHFNFFzTNPzb
LZVRmcDRvpQLmvvVGDGmpntJJwCWCnCPJwgJDrPDqM
QddMvdzlVfvdSQmGhmwLbGbmzbns
JtCCWqqZDsLpGhbGjD
FNrhqCTWMSRSrQQg
ZsBZJFsZSmmJsJSmrJrJrvsrdGdCQGQphMGwRMGQRGdbBChM
FlgfqNNNWnNnHfVnnHdbGwpwGWQhGdRMMdRM
LFnggHlDqDLvjDmZPcPmvP
CRHJWfvJvrQfrCsDlGGBszQBjjGB
LmPHVnMmpLlPssBPlDtd
MmMSZmVnncMFcmSVHvfSrffCwSvfbHWv
wsrJrpdJLsMCZDWL
BbLtGGbNmLQggqgQQtGgMmDCTnWZCZWZTmMmCZnT
qNBGNNgQcbbtGbbFBLVjfcfwHvrHHJHJcr
pCZCpdjBljhjBlpVccCpbDDwRWDsLhLbwDsDwsDw
HNgFSSNvSmdqwsFLFWLGttbw
gMMndNrzNHnzJZVlMCMCTcpc
CfsFNszCrrGzrsggsPfPVNVlqTdSjSqMTdSVTdLL
vRhcHllwJDmnJmDMMdhqSqpVMhdjdp
cvHRvwQBPZZlrQgz
TsFhCtQtQsBBLtBLPvgz
jjWZZjZSMNlNNjljNnlmjjfJLMBGGLvBdzPQpggJJLQzpg
wjbcmmlnQZmlrTsCFVwshwTr
nRGFnFjcdlwLSHSpNNnBfWHN
TgQvPbCMPRhbMPQvtQPvMCRBSHNQHBrQSNfWqpHHrWNWSf
PCgMbPvTZVDgtPRggtCCbgmmFJJLmcGFLjdmJFcDwJmm
dgWPssfdvQCLPLhL
pMtSMtpSmpMpFSMMFZjQCLbLQZZbVbVhNTLblZ
mpqcpzncfWwhzfRf
vntvVnRCsvpBpMjCpTpj
rQdZfhzczNzWcNLTpWgSvjjjpGpMSB
ZqNDQhfcNchLchQqcDqRHJtHVwnwbtvHsbVs
qtJGQgTrqtqQdQDgbGjPzZHWWzVjslPZlG
vBShwRRvvSRSvFvwLSvfcnfBWmHZHVWWHPzlNPWVWjZsWnWV
cLBFBFhCBLlwpFccFBFftqJDQdgdTDJJCbJgCCdg
wfmsPvPwNfvmfLNFvzzJbRMnllhlnLhRLC
gjtqDDTtjgpJcbnMTzCRnCCWhC
SDqtpGSStVtdqpgBVjBGZmFPJNJmffvfPsHZPZQd
HQMBBWrQQmPBvmBWnvrTnMSsbFfcfwgfCgscsmGgwgcJGg
NzzlJLthtlgswGFcwGst
JqNNRqpzhVRWTSQrrvSQ
mFpDZjvmtPPGvFjmmGTzTcFRbHczHTbzQgRS
fNdqhJsNrnnVNhwNVdrdsVczQCcwCMHSTCHgHCRzHgcM
JlgnNhsqVqNqNpPlvZvDDDGlZZ
"@ -split "`r`n"



$inventory    = [System.Collections.Generic.List[PSCustomObject]]::new()
$priorityhash = New-Object system.collections.hashtable

#region    - Hash
$priorityhash.'a'=1
$priorityhash.'b'=2
$priorityhash.'c'=3
$priorityhash.'d'=4
$priorityhash.'e'=5
$priorityhash.'f'=6
$priorityhash.'g'=7
$priorityhash.'h'=8
$priorityhash.'i'=9
$priorityhash.'j'=10
$priorityhash.'k'=11
$priorityhash.'l'=12
$priorityhash.'m'=13
$priorityhash.'n'=14
$priorityhash.'o'=15
$priorityhash.'p'=16
$priorityhash.'q'=17
$priorityhash.'r'=18
$priorityhash.'s'=19
$priorityhash.'t'=20
$priorityhash.'u'=21
$priorityhash.'v'=22
$priorityhash.'w'=23
$priorityhash.'x'=24
$priorityhash.'y'=25
$priorityhash.'z'=26
$priorityhash.'A'=27
$priorityhash.'B'=28
$priorityhash.'C'=29
$priorityhash.'D'=30
$priorityhash.'E'=31
$priorityhash.'F'=32
$priorityhash.'G'=33
$priorityhash.'H'=34
$priorityhash.'I'=35
$priorityhash.'J'=36
$priorityhash.'K'=37
$priorityhash.'L'=38
$priorityhash.'M'=39
$priorityhash.'N'=40
$priorityhash.'O'=41
$priorityhash.'P'=42
$priorityhash.'Q'=43
$priorityhash.'R'=44
$priorityhash.'S'=45
$priorityhash.'T'=46
$priorityhash.'U'=47
$priorityhash.'V'=48
$priorityhash.'W'=49
$priorityhash.'X'=50
$priorityhash.'Y'=51
$priorityhash.'Z'=52
#endregion - Hash

for ($i = 2; $i -le ($puzzleInput|measure).count ; $i=$i+3){ 
    $comp1   = ( $puzzleInput[$i-2] ).toCharArray()
    $comp2   = ( $puzzleInput[$i-1] ).toCharArray()
    $comp3   = ( $puzzleInput[$i]   ).toCharArray()
    
    $common = 
    foreach($c1 in $comp1){
        if( $comp1 -ccontains $c1 -and $comp2 -ccontains $c1 -and $comp3 -ccontains $c1){
            $c1
        }
    }

    $groupLetter = $common | select -Unique
    $inventory.add($priorityhash["$groupLetter"])
    

}

($inventory |measure -sum).sum
```
