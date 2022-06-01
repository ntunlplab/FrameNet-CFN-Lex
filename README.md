# NTU Chinese FrameNet Lexicon (CFN-Lex)
# Introduction
A total of 36K lexical units that cover 779 frames for FrameNet in Chinese. This resource is extracted from a large-scale bilingual corpus to achieve higher coverage in terms of lexical units, which is helpful in providing frame recommendations for annotation campaigns or constructing robust frame identification systems.

# Format
Each entry in the JSON format is a frame and its lexical units.

As the example shown as follows, words such as '客人', '來訪者', '遊客', '視察', ... could be the trigger for frame Visiting.
# Example
```yaml
{
  ...
  "Visiting": ['客人', '來訪者', '遊客', '視察', '到訪', '賓館', '招待所', '賓客', '審視', '訪問者', '住客', '做客', '顧客', '外國遊客', '迴訪', '招待', '主人', '貴賓', '旅遊', '探訪', '訪客', '來訪', '作客', '迴顧', '來客', '參觀', '客房', '旅客', '應邀', '邀請', '嘉賓', '外賓', '來賓']
  ...
}
```
# Download
[Traditional Chinese download link](http://nlg.csie.ntu.edu.tw/nlpresource/FrameNet/CFN-Lex/CFN_LEX_ZHTW.json).
[Simplified Chinese download link](http://nlg.csie.ntu.edu.tw/nlpresource/FrameNet/CFN-Lex/CFN_LEX_CN.json).

# How to Cite this Resource
Please cite the following paper when referring to CFN-Lex in academic publications and papers.

<sub>
Tsung-Han Yang, Hen-Hsen Huang, An-Zi Yen, and Hsin-Hsi Chen (2018). “Transfer of Frames from English FrameNet to Construct Chinese FrameNet: A Bilingual Corpus-based Approach.” 11th Edition of the Language Resources and Evaluation Conference (LREC 2018), May 7-12, 2018, Miyazaki, Japan.
</sub>
