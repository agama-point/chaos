# chaos
stochastic behavior of deterministic systems

---

```python
>>> def rp(x):
	return 4*x*(1-x)

>>> rp(0.1)
0.36000000000000004
>>>
>>> def rpn(x, n):
	for i in range(n):
		x = rp(x)
		print(i,x)

		
>>> rpn(0.1,10)
0 0.36000000000000004
1 0.9216
2 0.28901376000000006
3 0.8219392261226498
4 0.5854205387341974
5 0.970813326249438
6 0.11333924730376121
7 0.4019738492975123
8 0.9615634951138128
9 0.1478365599132853
>>> 



```
### Real Parabola

unambiguity is disturbed by a rounding error

---

https://www.agamapoint.com/chaos/

https://geoffboeing.com/2015/04/visualizing-chaos-and-randomness/


