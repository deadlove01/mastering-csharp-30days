# C# Mastery Plan – Combined + Extended Suggestions (2026 Edition)

**Approach**: Merge book depth + your topics + modern .NET 9/10 features  
**Time estimate**: 4–7 months (flexible pace)  
**Philosophy**: Read → Break → Benchmark → Teach

## Phase 0 – Setup & Mindset (1–2 weeks)
- .NET 9 SDK, BenchmarkDotNet, dotnet-trace, SharpLab.io
- Repo: CSharp-Mastery-2026
- Weekly habit: 1 blog post or internal lightning talk

## Phase 1 – Language Core via C# in Depth (Weeks 1–10)
Follow 4th edition structure → extend with C# 8–13 docs

- Weeks 1–2: Generics + collections basics (Ch 2)
- Weeks 3–5: LINQ mastery (Ch 3)
- Weeks 6–9: Async/await full depth (Ch 5–6)
- Week 10: Modern features (Ch 11–13 + C# 9–13 supplements)

**Extended**:
- Add source generators (enum extensions → concurrent wrappers)
- Use Span<T>/ref in collection exercises

## Phase 2 – Collections & Generics Performance (Weeks 11–14)
- Custom collections + benchmarks
- Immutable + concurrent collections shootout
- Project: Generic, AOT-friendly cache with source-generated serializers

## Phase 3 – Concurrency & Threading Power Tools (Weeks 15–20)
- Low-level (Interlocked, SpinWait) → high-level (Channels, Dataflow)
- Async + concurrent patterns (background workers, pipelines)
- Project: Real-time event processor (Channels + PLINQ + IAsyncEnumerable)

## Phase 4 – Modern .NET Superpowers (Weeks 21–26)
- Source generators (heavy focus – replace reflection)
- Minimal APIs + AOT compilation
- Primary constructors, required members, interceptors (C# 12+)
- Nullable reference types + static analysis

## Phase 5 – Mastery Validation & Teaching (Ongoing)
- Build microservice skeleton combining all topics
- Profile & optimize (counters, trace, heap analysis)
- Teach: 30-min talk per major topic
- Contribute: answer SO questions, small PRs to open-source

**Recommended extras**:
- Books: Concurrency in C# Cookbook (Cleary), CLR via C# (Richter – threading/GC)
- Blogs: Stephen Toub, Andrew Lock (source gen), Jon Skeet
- Tools: LINQPad, PerfView, dotnet-counters

By end you should:
- Explain most compiler transformations
- Write allocation-free hot paths
- Design safe concurrent systems
- Use metaprogramming (generators) confidently

Start with Chapter 2 this week. Ping with progress!