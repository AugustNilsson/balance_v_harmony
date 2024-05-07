# balance_v_harmony
Models for classifying balance v harmony text.
The two models only differ in that the harmony_balance_is_it_class_rob_la_23_may_05.rds model was trained using a language where "harmony" and "balance" were replaced by "it" to generalize better. This model had an AUC=.92, and the model including the harmony and balance words had an AUC=.93, i.e., harmony_balance_class_rob_la_23_may_05.rds. 

The models were trained on 7313 US participants answering two questions about balance and harmony, "What does balance [or harmony] mean to you?"
