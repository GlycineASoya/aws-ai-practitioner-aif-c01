# Foundation Models Performance

## Performance Metrics

1. ROUGE (Recall-Oriented Understudy for Gisting Evaluation)
   1. Definition: Set of metrics for evaluating automatic summarization and machine translation
   2. Two types:
      1. ROUGE-N (n-grams)
      2. ROUGE-L (longest common subsequence)
   3. Purpose: Measure the overlap between generated text and reference text
   4. The higher ROUGE score the better text quality
   5. N-gram - contiguous sequence of n items (for example, words or characters) from a give text or speech
2. BLUE (Bilingual Evaluation Understudy)
   1. Definition: Machine translation quality by comparing n-grams metric
   2. Limitation: there is a penalty for a brevity to prevent overly short translations
   3. Purpose: how many n-grams in the generated text appear in reference translations
3. BERT Score (Bidirectional Encoder Representation from Transformers)
   1. Definition: BERT embeddings (contextual represetation of text, where the meaning of a word depends on surrounding words) to evaluate text similarities, on a deep semantic (meaning) level
   2. Purpose: Measures how many n-grams in the generated text appear in reference translations

## Popular Benchmark Datasets

Purpose: to simplify, decrease cost, and automate the model performance evaluation

1. General Language Understanding Evaluation (GLUE) - focus on understanding tasks
2. SuperGLUE - enhanced GLUE for advanced evaluation
3. Stanford Question Answering Dataset (SQuAD) - question-awnsering capabilities
4. Workshop on Machine Translation (WMT) - machine translation systems

### Benefits of benchmarks

1. Standardization
2. Coverage - it covers full set of topics
3. Progress Tracking - monitoring of the model performance

## Business Objective Criteria

### Key considerations

1. Alignment with Business Objectives
2. Performance Metrics
3. User Feedback
4. Integration and Usability
