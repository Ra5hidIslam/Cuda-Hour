Structure (from your Targets page, made checkable)

Day	Task	Output
Mon, Wed, Fri	Explain one concept aloud for 5 min. Then read the vLLM or FlashAttention code that uses it for 55 min.	A note of about 10 lines: the concept, file:line, one question you can’t answer yet
Tue, Thu	Write one small kernel and profile it.	Kernel + ncu numbers committed
Sat	Draw one inference system design on paper.	A photo of the page
Sun	30 min. Reread the week’s notes.	3 lines: what is still unclear

Commit everything to one public repo (for example cuda-hour). The commit is your link.

Topic order (for interviews and your spec-decode niche)

1. Memory coalescing, then shared-memory bank conflicts (a transpose kernel).
2. Warp-shuffle reduction, then softmax (a fused softmax kernel).
3. Tiled GEMM: naive, then shared memory, then register tiling (measure GFLOPS at each step).
4. Online softmax in FlashAttention-2, read against the actual kernel.
5. The PagedAttention block table: the v1 attention backend in vLLM.
6. Spec-decode rejection sampling: the vLLM kernel. 

Week:9th Nov to 16th Nov

Monday: Memory Coalescing 

Tuesday:Shared memory bank conflicts(a transpose kernel)

Wednesday:Warp shuffle reduction

Thursday:A fused softmax kernel

Friday: Tiled GEMM

Saturday:Inference system design

Sunday:Reread week's notes
 
