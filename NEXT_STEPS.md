# Next Steps - Integration

1. Copy skeleton_bridge.py into Skeleton/tests/test_readiness_bridge.py
2. Add to Skeleton Makefile: `test-readiness: python tests/test_readiness_bridge.py`
3. Wire into .github/workflows as a job after unit tests.
4. Enforce in doctor cycle: fail if readiness < 80.
5. Bind to era on forge runs.
6. Clip mass in observe_run.

Handled as continuation. Direct implementation.
