# ATMT_Assignments
## Assignment3
The strategies we propose do not require any code changes. We preprocess the data with **[BPE implementation of Neural Machine Translation with subword units](https://github.com/gjwubyron/subword-nmt#best-practice-advice-for-byte-pair-encoding-in-nmt)**. For postprocess we also follow their advice. (i.e. sed -r 's/(@@ )|(@@ ?$)//g')

## Assignment5
Changes can be found in the translate_beam_uid, translate_beam_adapted, and beam. diverse_beam consists of the diverse results with a large gamma.
