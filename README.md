# MP1  
  
Setup: Place all files inside the default package rather than a dedicated one. I personally used IntelliJ for this.  
  
## Part 1 - Run TestDominatorFinder as an Application  
r0 := @this: GCD is dominated by r0 := @this: GCD  
specialinvoke r0.<java.lang.Object: void <init>()>() is dominated by r0 := @this: GCD  
specialinvoke r0.<java.lang.Object: void <init>()>() is dominated by specialinvoke r0.<java.lang.Object: void <init>()>()  
return is dominated by r0 := @this: GCD  
return is dominated by specialinvoke r0.<java.lang.Object: void <init>()>()  
return is dominated by return  
r0 := @parameter0: java.lang.String[] is dominated by r0 := @parameter0: java.lang.String[]  
$i2 = lengthof r0 is dominated by r0 := @parameter0: java.lang.String[]  
$i2 = lengthof r0 is dominated by $i2 = lengthof r0  
if $i2 >= 2 goto $r1 = r0[0] is dominated by r0 := @parameter0: java.lang.String[]  
if $i2 >= 2 goto $r1 = r0[0] is dominated by $i2 = lengthof r0  
if $i2 >= 2 goto $r1 = r0[0] is dominated by if $i2 >= 2 goto $r1 = r0[0]  
$r12 = <java.lang.System: java.io.PrintStream err> is dominated by r0 := @parameter0: java.lang.String[]  
$r12 = <java.lang.System: java.io.PrintStream err> is dominated by $i2 = lengthof r0  
$r12 = <java.lang.System: java.io.PrintStream err> is dominated by if $i2 >= 2 goto $r1 = r0[0]  
$r12 = <java.lang.System: java.io.PrintStream err> is dominated by $r12 = <java.lang.System: java.io.PrintStream err>  
virtualinvoke $r12.<java.io.PrintStream: void println(java.lang.String)>("java GCD int1 int2\nExample: java GCD 876 267") is dominated by r0 := @parameter0: java.lang.String[]  
virtualinvoke $r12.<java.io.PrintStream: void println(java.lang.String)>("java GCD int1 int2\nExample: java GCD 876 267") is dominated by $i2 = lengthof r0  
virtualinvoke $r12.<java.io.PrintStream: void println(java.lang.String)>("java GCD int1 int2\nExample: java GCD 876 267") is dominated by if $i2 >= 2 goto $r1 = r0[0]  
virtualinvoke $r12.<java.io.PrintStream: void println(java.lang.String)>("java GCD int1 int2\nExample: java GCD 876 267") is dominated by $r12 = <java.lang.System: java.io.PrintStream err>  
virtualinvoke $r12.<java.io.PrintStream: void println(java.lang.String)>("java GCD int1 int2\nExample: java GCD 876 267") is dominated by virtualinvoke $r12.<java.io.PrintStream: void println(java.lang.String)>("java GCD int1 int2\nExample: java GCD 876 267")  
return is dominated by r0 := @parameter0: java.lang.String[]  
return is dominated by $i2 = lengthof r0  
return is dominated by if $i2 >= 2 goto $r1 = r0[0]  
return is dominated by $r12 = <java.lang.System: java.io.PrintStream err>  
return is dominated by virtualinvoke $r12.<java.io.PrintStream: void println(java.lang.String)>("java GCD int1 int2\nExample: java GCD 876 267")  
return is dominated by return  
$r1 = r0[0] is dominated by r0 := @parameter0: java.lang.String[]  
$r1 = r0[0] is dominated by $i2 = lengthof r0  
$r1 = r0[0] is dominated by if $i2 >= 2 goto $r1 = r0[0]  
$r1 = r0[0] is dominated by $r1 = r0[0]  
i0 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r1) is dominated by r0 := @parameter0: java.lang.String[]  
i0 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r1) is dominated by $i2 = lengthof r0  
i0 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r1) is dominated by if $i2 >= 2 goto $r1 = r0[0]  
i0 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r1) is dominated by $r1 = r0[0]  
i0 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r1) is dominated by i0 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r1)  
$r2 = r0[1] is dominated by r0 := @parameter0: java.lang.String[]  
$r2 = r0[1] is dominated by $i2 = lengthof r0  
$r2 = r0[1] is dominated by if $i2 >= 2 goto $r1 = r0[0]  
$r2 = r0[1] is dominated by $r1 = r0[0]  
$r2 = r0[1] is dominated by i0 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r1)  
$r2 = r0[1] is dominated by $r2 = r0[1]  
i1 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r2) is dominated by r0 := @parameter0: java.lang.String[]  
i1 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r2) is dominated by $i2 = lengthof r0  
i1 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r2) is dominated by if $i2 >= 2 goto $r1 = r0[0]  
i1 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r2) is dominated by $r1 = r0[0]  
i1 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r2) is dominated by i0 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r1)  
i1 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r2) is dominated by $r2 = r0[1]  
i1 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r2) is dominated by i1 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r2)  
$r4 = <java.lang.System: java.io.PrintStream out> is dominated by r0 := @parameter0: java.lang.String[]  
$r4 = <java.lang.System: java.io.PrintStream out> is dominated by $i2 = lengthof r0  
$r4 = <java.lang.System: java.io.PrintStream out> is dominated by if $i2 >= 2 goto $r1 = r0[0]  
$r4 = <java.lang.System: java.io.PrintStream out> is dominated by $r1 = r0[0]  
$r4 = <java.lang.System: java.io.PrintStream out> is dominated by i0 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r1)  
$r4 = <java.lang.System: java.io.PrintStream out> is dominated by $r2 = r0[1]  
$r4 = <java.lang.System: java.io.PrintStream out> is dominated by i1 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r2)  
$r4 = <java.lang.System: java.io.PrintStream out> is dominated by $r4 = <java.lang.System: java.io.PrintStream out>  
$r3 = new java.lang.StringBuilder is dominated by r0 := @parameter0: java.lang.String[]  
$r3 = new java.lang.StringBuilder is dominated by $i2 = lengthof r0  
$r3 = new java.lang.StringBuilder is dominated by if $i2 >= 2 goto $r1 = r0[0]  
$r3 = new java.lang.StringBuilder is dominated by $r1 = r0[0]  
$r3 = new java.lang.StringBuilder is dominated by i0 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r1)  
$r3 = new java.lang.StringBuilder is dominated by $r2 = r0[1]  
$r3 = new java.lang.StringBuilder is dominated by i1 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r2)  
$r3 = new java.lang.StringBuilder is dominated by $r4 = <java.lang.System: java.io.PrintStream out>  
$r3 = new java.lang.StringBuilder is dominated by $r3 = new java.lang.StringBuilder  
specialinvoke $r3.<java.lang.StringBuilder: void <init>()>() is dominated by r0 := @parameter0: java.lang.String[]  
specialinvoke $r3.<java.lang.StringBuilder: void <init>()>() is dominated by $i2 = lengthof r0  
specialinvoke $r3.<java.lang.StringBuilder: void <init>()>() is dominated by if $i2 >= 2 goto $r1 = r0[0]  
specialinvoke $r3.<java.lang.StringBuilder: void <init>()>() is dominated by $r1 = r0[0]  
specialinvoke $r3.<java.lang.StringBuilder: void <init>()>() is dominated by i0 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r1)  
specialinvoke $r3.<java.lang.StringBuilder: void <init>()>() is dominated by $r2 = r0[1]  
specialinvoke $r3.<java.lang.StringBuilder: void <init>()>() is dominated by i1 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r2)  
specialinvoke $r3.<java.lang.StringBuilder: void <init>()>() is dominated by $r4 = <java.lang.System: java.io.PrintStream out>  
specialinvoke $r3.<java.lang.StringBuilder: void <init>()>() is dominated by $r3 = new java.lang.StringBuilder  
specialinvoke $r3.<java.lang.StringBuilder: void <init>()>() is dominated by specialinvoke $r3.<java.lang.StringBuilder: void <init>()>()  
$r5 = virtualinvoke $r3.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>("gcd(") is dominated by r0 := @parameter0: java.lang.String[]  
$r5 = virtualinvoke $r3.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>("gcd(") is dominated by $i2 = lengthof r0  
$r5 = virtualinvoke $r3.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>("gcd(") is dominated by if $i2 >= 2 goto $r1 = r0[0]  
$r5 = virtualinvoke $r3.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>("gcd(") is dominated by $r1 = r0[0]  
$r5 = virtualinvoke $r3.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>("gcd(") is dominated by i0 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r1)  
$r5 = virtualinvoke $r3.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>("gcd(") is dominated by $r2 = r0[1]  
$r5 = virtualinvoke $r3.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>("gcd(") is dominated by i1 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r2)  
$r5 = virtualinvoke $r3.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>("gcd(") is dominated by $r4 = <java.lang.System: java.io.PrintStream out>  
$r5 = virtualinvoke $r3.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>("gcd(") is dominated by $r3 = new java.lang.StringBuilder  
$r5 = virtualinvoke $r3.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>("gcd(") is dominated by specialinvoke $r3.<java.lang.StringBuilder: void <init>()>()  
$r5 = virtualinvoke $r3.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>("gcd(") is dominated by $r5 = virtualinvoke $r3.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>("gcd(")  
$r6 = virtualinvoke $r5.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i0) is dominated by r0 := @parameter0: java.lang.String[]  
$r6 = virtualinvoke $r5.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i0) is dominated by $i2 = lengthof r0  
$r6 = virtualinvoke $r5.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i0) is dominated by if $i2 >= 2 goto $r1 = r0[0]  
$r6 = virtualinvoke $r5.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i0) is dominated by $r1 = r0[0]  
$r6 = virtualinvoke $r5.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i0) is dominated by i0 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r1)  
$r6 = virtualinvoke $r5.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i0) is dominated by $r2 = r0[1]  
$r6 = virtualinvoke $r5.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i0) is dominated by i1 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r2)  
$r6 = virtualinvoke $r5.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i0) is dominated by $r4 = <java.lang.System: java.io.PrintStream out>  
$r6 = virtualinvoke $r5.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i0) is dominated by $r3 = new java.lang.StringBuilder  
$r6 = virtualinvoke $r5.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i0) is dominated by specialinvoke $r3.<java.lang.StringBuilder: void <init>()>()  
$r6 = virtualinvoke $r5.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i0) is dominated by $r5 = virtualinvoke $r3.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>("gcd(")  
$r6 = virtualinvoke $r5.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i0) is dominated by $r6 = virtualinvoke $r5.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i0)  
$r7 = virtualinvoke $r6.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(", ") is dominated by r0 := @parameter0: java.lang.String[]  
$r7 = virtualinvoke $r6.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(", ") is dominated by $i2 = lengthof r0  
$r7 = virtualinvoke $r6.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(", ") is dominated by if $i2 >= 2 goto $r1 = r0[0]  
$r7 = virtualinvoke $r6.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(", ") is dominated by $r1 = r0[0]  
$r7 = virtualinvoke $r6.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(", ") is dominated by i0 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r1)  
$r7 = virtualinvoke $r6.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(", ") is dominated by $r2 = r0[1]  
$r7 = virtualinvoke $r6.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(", ") is dominated by i1 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r2)  
$r7 = virtualinvoke $r6.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(", ") is dominated by $r4 = <java.lang.System: java.io.PrintStream out>  
$r7 = virtualinvoke $r6.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(", ") is dominated by $r3 = new java.lang.StringBuilder  
$r7 = virtualinvoke $r6.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(", ") is dominated by specialinvoke $r3.<java.lang.StringBuilder: void <init>()>()  
$r7 = virtualinvoke $r6.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(", ") is dominated by $r5 = virtualinvoke $r3.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>("gcd(")  
$r7 = virtualinvoke $r6.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(", ") is dominated by $r6 = virtualinvoke $r5.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i0)  
$r7 = virtualinvoke $r6.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(", ") is dominated by $r7 = virtualinvoke $r6.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(", ")  
$r8 = virtualinvoke $r7.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i1) is dominated by r0 := @parameter0: java.lang.String[]  
$r8 = virtualinvoke $r7.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i1) is dominated by $i2 = lengthof r0  
$r8 = virtualinvoke $r7.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i1) is dominated by if $i2 >= 2 goto $r1 = r0[0]  
$r8 = virtualinvoke $r7.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i1) is dominated by $r1 = r0[0]  
$r8 = virtualinvoke $r7.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i1) is dominated by i0 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r1)  
$r8 = virtualinvoke $r7.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i1) is dominated by $r2 = r0[1]  
$r8 = virtualinvoke $r7.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i1) is dominated by i1 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r2)  
$r8 = virtualinvoke $r7.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i1) is dominated by $r4 = <java.lang.System: java.io.PrintStream out>  
$r8 = virtualinvoke $r7.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i1) is dominated by $r3 = new java.lang.StringBuilder  
$r8 = virtualinvoke $r7.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i1) is dominated by specialinvoke $r3.<java.lang.StringBuilder: void <init>()>()  
$r8 = virtualinvoke $r7.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i1) is dominated by $r5 = virtualinvoke $r3.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>("gcd(")  
$r8 = virtualinvoke $r7.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i1) is dominated by $r6 = virtualinvoke $r5.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i0)  
$r8 = virtualinvoke $r7.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i1) is dominated by $r7 = virtualinvoke $r6.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(", ")  
$r8 = virtualinvoke $r7.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i1) is dominated by $r8 = virtualinvoke $r7.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i1)  
$r9 = virtualinvoke $r8.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(") = ") is dominated by r0 := @parameter0: java.lang.String[]  
$r9 = virtualinvoke $r8.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(") = ") is dominated by $i2 = lengthof r0  
$r9 = virtualinvoke $r8.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(") = ") is dominated by if $i2 >= 2 goto $r1 = r0[0]  
$r9 = virtualinvoke $r8.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(") = ") is dominated by $r1 = r0[0]  
$r9 = virtualinvoke $r8.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(") = ") is dominated by i0 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r1)  
$r9 = virtualinvoke $r8.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(") = ") is dominated by $r2 = r0[1]  
$r9 = virtualinvoke $r8.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(") = ") is dominated by i1 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r2)  
$r9 = virtualinvoke $r8.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(") = ") is dominated by $r4 = <java.lang.System: java.io.PrintStream out>  
$r9 = virtualinvoke $r8.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(") = ") is dominated by $r3 = new java.lang.StringBuilder  
$r9 = virtualinvoke $r8.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(") = ") is dominated by specialinvoke $r3.<java.lang.StringBuilder: void <init>()>()  
$r9 = virtualinvoke $r8.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(") = ") is dominated by $r5 = virtualinvoke $r3.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>("gcd(")  
$r9 = virtualinvoke $r8.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(") = ") is dominated by $r6 = virtualinvoke $r5.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i0)  
$r9 = virtualinvoke $r8.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(") = ") is dominated by $r7 = virtualinvoke $r6.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(", ")  
$r9 = virtualinvoke $r8.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(") = ") is dominated by $r8 = virtualinvoke $r7.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i1)  
$r9 = virtualinvoke $r8.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(") = ") is dominated by $r9 = virtualinvoke $r8.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(") = ")  
$i3 = staticinvoke <GCD: int gcd(int,int)>(i0, i1) is dominated by r0 := @parameter0: java.lang.String[]  
$i3 = staticinvoke <GCD: int gcd(int,int)>(i0, i1) is dominated by $i2 = lengthof r0  
$i3 = staticinvoke <GCD: int gcd(int,int)>(i0, i1) is dominated by if $i2 >= 2 goto $r1 = r0[0]  
$i3 = staticinvoke <GCD: int gcd(int,int)>(i0, i1) is dominated by $r1 = r0[0]  
$i3 = staticinvoke <GCD: int gcd(int,int)>(i0, i1) is dominated by i0 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r1)  
$i3 = staticinvoke <GCD: int gcd(int,int)>(i0, i1) is dominated by $r2 = r0[1]  
$i3 = staticinvoke <GCD: int gcd(int,int)>(i0, i1) is dominated by i1 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r2)  
$i3 = staticinvoke <GCD: int gcd(int,int)>(i0, i1) is dominated by $r4 = <java.lang.System: java.io.PrintStream out>  
$i3 = staticinvoke <GCD: int gcd(int,int)>(i0, i1) is dominated by $r3 = new java.lang.StringBuilder  
$i3 = staticinvoke <GCD: int gcd(int,int)>(i0, i1) is dominated by specialinvoke $r3.<java.lang.StringBuilder: void <init>()>()  
$i3 = staticinvoke <GCD: int gcd(int,int)>(i0, i1) is dominated by $r5 = virtualinvoke $r3.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>("gcd(")  
$i3 = staticinvoke <GCD: int gcd(int,int)>(i0, i1) is dominated by $r6 = virtualinvoke $r5.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i0)  
$i3 = staticinvoke <GCD: int gcd(int,int)>(i0, i1) is dominated by $r7 = virtualinvoke $r6.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(", ")  
$i3 = staticinvoke <GCD: int gcd(int,int)>(i0, i1) is dominated by $r8 = virtualinvoke $r7.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i1)  
$i3 = staticinvoke <GCD: int gcd(int,int)>(i0, i1) is dominated by $r9 = virtualinvoke $r8.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(") = ")  
$i3 = staticinvoke <GCD: int gcd(int,int)>(i0, i1) is dominated by $i3 = staticinvoke <GCD: int gcd(int,int)>(i0, i1)  
$r10 = virtualinvoke $r9.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>($i3) is dominated by r0 := @parameter0: java.lang.String[]  
$r10 = virtualinvoke $r9.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>($i3) is dominated by $i2 = lengthof r0  
$r10 = virtualinvoke $r9.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>($i3) is dominated by if $i2 >= 2 goto $r1 = r0[0]  
$r10 = virtualinvoke $r9.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>($i3) is dominated by $r1 = r0[0]  
$r10 = virtualinvoke $r9.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>($i3) is dominated by i0 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r1)  
$r10 = virtualinvoke $r9.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>($i3) is dominated by $r2 = r0[1]  
$r10 = virtualinvoke $r9.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>($i3) is dominated by i1 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r2)  
$r10 = virtualinvoke $r9.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>($i3) is dominated by $r4 = <java.lang.System: java.io.PrintStream out>  
$r10 = virtualinvoke $r9.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>($i3) is dominated by $r3 = new java.lang.StringBuilder  
$r10 = virtualinvoke $r9.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>($i3) is dominated by specialinvoke $r3.<java.lang.StringBuilder: void <init>()>()  
$r10 = virtualinvoke $r9.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>($i3) is dominated by $r5 = virtualinvoke $r3.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>("gcd(")  
$r10 = virtualinvoke $r9.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>($i3) is dominated by $r6 = virtualinvoke $r5.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i0)  
$r10 = virtualinvoke $r9.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>($i3) is dominated by $r7 = virtualinvoke $r6.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(", ")  
$r10 = virtualinvoke $r9.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>($i3) is dominated by $r8 = virtualinvoke $r7.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i1)  
$r10 = virtualinvoke $r9.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>($i3) is dominated by $r9 = virtualinvoke $r8.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(") = ")  
$r10 = virtualinvoke $r9.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>($i3) is dominated by $i3 = staticinvoke <GCD: int gcd(int,int)>(i0, i1)  
$r10 = virtualinvoke $r9.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>($i3) is dominated by $r10 = virtualinvoke $r9.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>($i3)  
$r11 = virtualinvoke $r10.<java.lang.StringBuilder: java.lang.String toString()>() is dominated by r0 := @parameter0: java.lang.String[]  
$r11 = virtualinvoke $r10.<java.lang.StringBuilder: java.lang.String toString()>() is dominated by $i2 = lengthof r0  
$r11 = virtualinvoke $r10.<java.lang.StringBuilder: java.lang.String toString()>() is dominated by if $i2 >= 2 goto $r1 = r0[0]  
$r11 = virtualinvoke $r10.<java.lang.StringBuilder: java.lang.String toString()>() is dominated by $r1 = r0[0]  
$r11 = virtualinvoke $r10.<java.lang.StringBuilder: java.lang.String toString()>() is dominated by i0 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r1)  
$r11 = virtualinvoke $r10.<java.lang.StringBuilder: java.lang.String toString()>() is dominated by $r2 = r0[1]  
$r11 = virtualinvoke $r10.<java.lang.StringBuilder: java.lang.String toString()>() is dominated by i1 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r2)  
$r11 = virtualinvoke $r10.<java.lang.StringBuilder: java.lang.String toString()>() is dominated by $r4 = <java.lang.System: java.io.PrintStream out>  
$r11 = virtualinvoke $r10.<java.lang.StringBuilder: java.lang.String toString()>() is dominated by $r3 = new java.lang.StringBuilder  
$r11 = virtualinvoke $r10.<java.lang.StringBuilder: java.lang.String toString()>() is dominated by specialinvoke $r3.<java.lang.StringBuilder: void <init>()>()  
$r11 = virtualinvoke $r10.<java.lang.StringBuilder: java.lang.String toString()>() is dominated by $r5 = virtualinvoke $r3.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>("gcd(")  
$r11 = virtualinvoke $r10.<java.lang.StringBuilder: java.lang.String toString()>() is dominated by $r6 = virtualinvoke $r5.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i0)  
$r11 = virtualinvoke $r10.<java.lang.StringBuilder: java.lang.String toString()>() is dominated by $r7 = virtualinvoke $r6.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(", ")  
$r11 = virtualinvoke $r10.<java.lang.StringBuilder: java.lang.String toString()>() is dominated by $r8 = virtualinvoke $r7.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i1)  
$r11 = virtualinvoke $r10.<java.lang.StringBuilder: java.lang.String toString()>() is dominated by $r9 = virtualinvoke $r8.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(") = ")  
$r11 = virtualinvoke $r10.<java.lang.StringBuilder: java.lang.String toString()>() is dominated by $i3 = staticinvoke <GCD: int gcd(int,int)>(i0, i1)  
$r11 = virtualinvoke $r10.<java.lang.StringBuilder: java.lang.String toString()>() is dominated by $r10 = virtualinvoke $r9.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>($i3)  
$r11 = virtualinvoke $r10.<java.lang.StringBuilder: java.lang.String toString()>() is dominated by $r11 = virtualinvoke $r10.<java.lang.StringBuilder: java.lang.String toString()>()  
virtualinvoke $r4.<java.io.PrintStream: void println(java.lang.String)>($r11) is dominated by r0 := @parameter0: java.lang.String[]  
virtualinvoke $r4.<java.io.PrintStream: void println(java.lang.String)>($r11) is dominated by $i2 = lengthof r0  
virtualinvoke $r4.<java.io.PrintStream: void println(java.lang.String)>($r11) is dominated by if $i2 >= 2 goto $r1 = r0[0]  
virtualinvoke $r4.<java.io.PrintStream: void println(java.lang.String)>($r11) is dominated by $r1 = r0[0]  
virtualinvoke $r4.<java.io.PrintStream: void println(java.lang.String)>($r11) is dominated by i0 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r1)  
virtualinvoke $r4.<java.io.PrintStream: void println(java.lang.String)>($r11) is dominated by $r2 = r0[1]  
virtualinvoke $r4.<java.io.PrintStream: void println(java.lang.String)>($r11) is dominated by i1 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r2)  
virtualinvoke $r4.<java.io.PrintStream: void println(java.lang.String)>($r11) is dominated by $r4 = <java.lang.System: java.io.PrintStream out>  
virtualinvoke $r4.<java.io.PrintStream: void println(java.lang.String)>($r11) is dominated by $r3 = new java.lang.StringBuilder  
virtualinvoke $r4.<java.io.PrintStream: void println(java.lang.String)>($r11) is dominated by specialinvoke $r3.<java.lang.StringBuilder: void <init>()>()  
virtualinvoke $r4.<java.io.PrintStream: void println(java.lang.String)>($r11) is dominated by $r5 = virtualinvoke $r3.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>("gcd(")  
virtualinvoke $r4.<java.io.PrintStream: void println(java.lang.String)>($r11) is dominated by $r6 = virtualinvoke $r5.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i0)  
virtualinvoke $r4.<java.io.PrintStream: void println(java.lang.String)>($r11) is dominated by $r7 = virtualinvoke $r6.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(", ")  
virtualinvoke $r4.<java.io.PrintStream: void println(java.lang.String)>($r11) is dominated by $r8 = virtualinvoke $r7.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i1)  
virtualinvoke $r4.<java.io.PrintStream: void println(java.lang.String)>($r11) is dominated by $r9 = virtualinvoke $r8.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(") = ")  
virtualinvoke $r4.<java.io.PrintStream: void println(java.lang.String)>($r11) is dominated by $i3 = staticinvoke <GCD: int gcd(int,int)>(i0, i1)  
virtualinvoke $r4.<java.io.PrintStream: void println(java.lang.String)>($r11) is dominated by $r10 = virtualinvoke $r9.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>($i3)  
virtualinvoke $r4.<java.io.PrintStream: void println(java.lang.String)>($r11) is dominated by $r11 = virtualinvoke $r10.<java.lang.StringBuilder: java.lang.String toString()>()  
virtualinvoke $r4.<java.io.PrintStream: void println(java.lang.String)>($r11) is dominated by virtualinvoke $r4.<java.io.PrintStream: void println(java.lang.String)>($r11)  
return is dominated by r0 := @parameter0: java.lang.String[]  
return is dominated by $i2 = lengthof r0  
return is dominated by if $i2 >= 2 goto $r1 = r0[0]  
return is dominated by $r1 = r0[0]  
return is dominated by i0 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r1)  
return is dominated by $r2 = r0[1]  
return is dominated by i1 = staticinvoke <java.lang.Integer: int parseInt(java.lang.String)>($r2)  
return is dominated by $r4 = <java.lang.System: java.io.PrintStream out>  
return is dominated by $r3 = new java.lang.StringBuilder  
return is dominated by specialinvoke $r3.<java.lang.StringBuilder: void <init>()>()  
return is dominated by $r5 = virtualinvoke $r3.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>("gcd(")  
return is dominated by $r6 = virtualinvoke $r5.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i0)  
return is dominated by $r7 = virtualinvoke $r6.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(", ")  
return is dominated by $r8 = virtualinvoke $r7.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>(i1)  
return is dominated by $r9 = virtualinvoke $r8.<java.lang.StringBuilder: java.lang.StringBuilder append(java.lang.String)>(") = ")  
return is dominated by $i3 = staticinvoke <GCD: int gcd(int,int)>(i0, i1)  
return is dominated by $r10 = virtualinvoke $r9.<java.lang.StringBuilder: java.lang.StringBuilder append(int)>($i3)  
return is dominated by $r11 = virtualinvoke $r10.<java.lang.StringBuilder: java.lang.String toString()>()  
return is dominated by virtualinvoke $r4.<java.io.PrintStream: void println(java.lang.String)>($r11)  
return is dominated by return  
i0 := @parameter0: int is dominated by i0 := @parameter0: int  
i1 := @parameter1: int is dominated by i0 := @parameter0: int  
i1 := @parameter1: int is dominated by i1 := @parameter1: int  
if i0 <= i1 goto i8 = i0 is dominated by i0 := @parameter0: int  
if i0 <= i1 goto i8 = i0 is dominated by i1 := @parameter1: int  
if i0 <= i1 goto i8 = i0 is dominated by if i0 <= i1 goto i8 = i0  
i7 = i1 is dominated by i0 := @parameter0: int  
i7 = i1 is dominated by i1 := @parameter1: int  
i7 = i1 is dominated by if i0 <= i1 goto i8 = i0  
i7 = i1 is dominated by i7 = i1  
if i7 < 1 goto (branch) is dominated by i0 := @parameter0: int  
if i7 < 1 goto (branch) is dominated by i1 := @parameter1: int  
if i7 < 1 goto (branch) is dominated by if i0 <= i1 goto i8 = i0  
if i7 < 1 goto (branch) is dominated by i7 = i1  
if i7 < 1 goto (branch) is dominated by if i7 < 1 goto (branch)  
$i5 = i0 % i7 is dominated by i0 := @parameter0: int  
$i5 = i0 % i7 is dominated by i1 := @parameter1: int  
$i5 = i0 % i7 is dominated by if i0 <= i1 goto i8 = i0  
$i5 = i0 % i7 is dominated by i7 = i1  
$i5 = i0 % i7 is dominated by if i7 < 1 goto (branch)  
$i5 = i0 % i7 is dominated by $i5 = i0 % i7  
if $i5 != 0 goto i7 = i7 + -1 is dominated by i0 := @parameter0: int  
if $i5 != 0 goto i7 = i7 + -1 is dominated by i1 := @parameter1: int  
if $i5 != 0 goto i7 = i7 + -1 is dominated by if i0 <= i1 goto i8 = i0  
if $i5 != 0 goto i7 = i7 + -1 is dominated by i7 = i1  
if $i5 != 0 goto i7 = i7 + -1 is dominated by if i7 < 1 goto (branch)  
if $i5 != 0 goto i7 = i7 + -1 is dominated by $i5 = i0 % i7  
if $i5 != 0 goto i7 = i7 + -1 is dominated by if $i5 != 0 goto i7 = i7 + -1  
$i6 = i1 % i7 is dominated by i0 := @parameter0: int  
$i6 = i1 % i7 is dominated by i1 := @parameter1: int  
$i6 = i1 % i7 is dominated by if i0 <= i1 goto i8 = i0  
$i6 = i1 % i7 is dominated by i7 = i1  
$i6 = i1 % i7 is dominated by if i7 < 1 goto (branch)  
$i6 = i1 % i7 is dominated by $i5 = i0 % i7  
$i6 = i1 % i7 is dominated by if $i5 != 0 goto i7 = i7 + -1  
$i6 = i1 % i7 is dominated by $i6 = i1 % i7  
if $i6 != 0 goto i7 = i7 + -1 is dominated by i0 := @parameter0: int  
if $i6 != 0 goto i7 = i7 + -1 is dominated by i1 := @parameter1: int  
if $i6 != 0 goto i7 = i7 + -1 is dominated by if i0 <= i1 goto i8 = i0  
if $i6 != 0 goto i7 = i7 + -1 is dominated by i7 = i1  
if $i6 != 0 goto i7 = i7 + -1 is dominated by if i7 < 1 goto (branch)  
if $i6 != 0 goto i7 = i7 + -1 is dominated by $i5 = i0 % i7  
if $i6 != 0 goto i7 = i7 + -1 is dominated by if $i5 != 0 goto i7 = i7 + -1  
if $i6 != 0 goto i7 = i7 + -1 is dominated by $i6 = i1 % i7  
if $i6 != 0 goto i7 = i7 + -1 is dominated by if $i6 != 0 goto i7 = i7 + -1  
return i7 is dominated by i0 := @parameter0: int  
return i7 is dominated by i1 := @parameter1: int  
return i7 is dominated by if i0 <= i1 goto i8 = i0  
return i7 is dominated by i7 = i1  
return i7 is dominated by if i7 < 1 goto (branch)  
return i7 is dominated by $i5 = i0 % i7  
return i7 is dominated by if $i5 != 0 goto i7 = i7 + -1  
return i7 is dominated by $i6 = i1 % i7  
return i7 is dominated by if $i6 != 0 goto i7 = i7 + -1  
return i7 is dominated by return i7  
i7 = i7 + -1 is dominated by i0 := @parameter0: int  
i7 = i7 + -1 is dominated by i1 := @parameter1: int  
i7 = i7 + -1 is dominated by if i0 <= i1 goto i8 = i0  
i7 = i7 + -1 is dominated by i7 = i1  
i7 = i7 + -1 is dominated by if i7 < 1 goto (branch)  
i7 = i7 + -1 is dominated by $i5 = i0 % i7  
i7 = i7 + -1 is dominated by if $i5 != 0 goto i7 = i7 + -1  
i7 = i7 + -1 is dominated by i7 = i7 + -1  
goto [?= (branch)] is dominated by i0 := @parameter0: int  
goto [?= (branch)] is dominated by i1 := @parameter1: int  
goto [?= (branch)] is dominated by if i0 <= i1 goto i8 = i0  
goto [?= (branch)] is dominated by i7 = i1  
goto [?= (branch)] is dominated by if i7 < 1 goto (branch)  
goto [?= (branch)] is dominated by $i5 = i0 % i7  
goto [?= (branch)] is dominated by if $i5 != 0 goto i7 = i7 + -1  
goto [?= (branch)] is dominated by i7 = i7 + -1  
goto [?= (branch)] is dominated by goto [?= (branch)]  
goto [?= return 1] is dominated by i0 := @parameter0: int  
goto [?= return 1] is dominated by i1 := @parameter1: int  
goto [?= return 1] is dominated by if i0 <= i1 goto i8 = i0  
goto [?= return 1] is dominated by i7 = i1  
goto [?= return 1] is dominated by if i7 < 1 goto (branch)  
goto [?= return 1] is dominated by goto [?= return 1]  
i8 = i0 is dominated by i0 := @parameter0: int  
i8 = i0 is dominated by i1 := @parameter1: int  
i8 = i0 is dominated by if i0 <= i1 goto i8 = i0  
i8 = i0 is dominated by i8 = i0  
if i8 < 1 goto return 1 is dominated by i0 := @parameter0: int  
if i8 < 1 goto return 1 is dominated by i1 := @parameter1: int  
if i8 < 1 goto return 1 is dominated by if i0 <= i1 goto i8 = i0  
if i8 < 1 goto return 1 is dominated by i8 = i0  
if i8 < 1 goto return 1 is dominated by if i8 < 1 goto return 1  
$i3 = i0 % i8 is dominated by i0 := @parameter0: int  
$i3 = i0 % i8 is dominated by i1 := @parameter1: int  
$i3 = i0 % i8 is dominated by if i0 <= i1 goto i8 = i0  
$i3 = i0 % i8 is dominated by i8 = i0  
$i3 = i0 % i8 is dominated by if i8 < 1 goto return 1  
$i3 = i0 % i8 is dominated by $i3 = i0 % i8  
if $i3 != 0 goto i8 = i8 + -1 is dominated by i0 := @parameter0: int  
if $i3 != 0 goto i8 = i8 + -1 is dominated by i1 := @parameter1: int  
if $i3 != 0 goto i8 = i8 + -1 is dominated by if i0 <= i1 goto i8 = i0  
if $i3 != 0 goto i8 = i8 + -1 is dominated by i8 = i0  
if $i3 != 0 goto i8 = i8 + -1 is dominated by if i8 < 1 goto return 1  
if $i3 != 0 goto i8 = i8 + -1 is dominated by $i3 = i0 % i8  
if $i3 != 0 goto i8 = i8 + -1 is dominated by if $i3 != 0 goto i8 = i8 + -1  
$i4 = i1 % i8 is dominated by i0 := @parameter0: int  
$i4 = i1 % i8 is dominated by i1 := @parameter1: int  
$i4 = i1 % i8 is dominated by if i0 <= i1 goto i8 = i0  
$i4 = i1 % i8 is dominated by i8 = i0  
$i4 = i1 % i8 is dominated by if i8 < 1 goto return 1  
$i4 = i1 % i8 is dominated by $i3 = i0 % i8  
$i4 = i1 % i8 is dominated by if $i3 != 0 goto i8 = i8 + -1  
$i4 = i1 % i8 is dominated by $i4 = i1 % i8  
if $i4 != 0 goto i8 = i8 + -1 is dominated by i0 := @parameter0: int  
if $i4 != 0 goto i8 = i8 + -1 is dominated by i1 := @parameter1: int  
if $i4 != 0 goto i8 = i8 + -1 is dominated by if i0 <= i1 goto i8 = i0  
if $i4 != 0 goto i8 = i8 + -1 is dominated by i8 = i0  
if $i4 != 0 goto i8 = i8 + -1 is dominated by if i8 < 1 goto return 1  
if $i4 != 0 goto i8 = i8 + -1 is dominated by $i3 = i0 % i8  
if $i4 != 0 goto i8 = i8 + -1 is dominated by if $i3 != 0 goto i8 = i8 + -1  
if $i4 != 0 goto i8 = i8 + -1 is dominated by $i4 = i1 % i8  
if $i4 != 0 goto i8 = i8 + -1 is dominated by if $i4 != 0 goto i8 = i8 + -1  
return i8 is dominated by i0 := @parameter0: int  
return i8 is dominated by i1 := @parameter1: int  
return i8 is dominated by if i0 <= i1 goto i8 = i0  
return i8 is dominated by i8 = i0  
return i8 is dominated by if i8 < 1 goto return 1  
return i8 is dominated by $i3 = i0 % i8  
return i8 is dominated by if $i3 != 0 goto i8 = i8 + -1  
return i8 is dominated by $i4 = i1 % i8  
return i8 is dominated by if $i4 != 0 goto i8 = i8 + -1  
return i8 is dominated by return i8  
i8 = i8 + -1 is dominated by i0 := @parameter0: int  
i8 = i8 + -1 is dominated by i1 := @parameter1: int  
i8 = i8 + -1 is dominated by if i0 <= i1 goto i8 = i0  
i8 = i8 + -1 is dominated by i8 = i0  
i8 = i8 + -1 is dominated by if i8 < 1 goto return 1  
i8 = i8 + -1 is dominated by $i3 = i0 % i8  
i8 = i8 + -1 is dominated by if $i3 != 0 goto i8 = i8 + -1  
i8 = i8 + -1 is dominated by i8 = i8 + -1  
goto [?= (branch)] is dominated by i0 := @parameter0: int  
goto [?= (branch)] is dominated by i1 := @parameter1: int  
goto [?= (branch)] is dominated by if i0 <= i1 goto i8 = i0  
goto [?= (branch)] is dominated by i8 = i0  
goto [?= (branch)] is dominated by if i8 < 1 goto return 1  
goto [?= (branch)] is dominated by $i3 = i0 % i8  
goto [?= (branch)] is dominated by if $i3 != 0 goto i8 = i8 + -1  
goto [?= (branch)] is dominated by i8 = i8 + -1  
goto [?= (branch)] is dominated by goto [?= (branch)]  
return 1 is dominated by i0 := @parameter0: int  
return 1 is dominated by i1 := @parameter1: int  
return 1 is dominated by if i0 <= i1 goto i8 = i0  
return 1 is dominated by return 1  
                                     
## Part 2 - Run TestSootCallGraph as an Application and pass in either "cha" or "pta" as arguments  
  
### CHA Output:  
<Example: Animal selectAnimal()> may call <Cat: void <init>()>  
<Example: void main(java.lang.String[])> may call <java.lang.System: void <clinit>()>  
<Example: void main(java.lang.String[])> may call <Cat: void saySomething()>  
<Example: void main(java.lang.String[])> may call <Fish: void saySomething()>  
<Example: void main(java.lang.String[])> may call <java.io.PrintStream: void println(java.lang.String)>  
<Example: void main(java.lang.String[])> may call <java.io.PrintStream: void println(java.lang.String)>  
<Example: void main(java.lang.String[])> may call <java.lang.Object: void <clinit>()>  
<Example: void main(java.lang.String[])> may call <Example: Animal selectAnimal()>  
<Animal: void <init>()> may call <java.lang.Object: void <init>()>  
<Cat: void <init>()> may call <Animal: void <init>()>  
<Cat: void saySomething()> may call <java.lang.System: void <clinit>()>  
<Cat: void saySomething()> may call <java.io.PrintStream: void println(java.lang.String)>  
<Cat: void saySomething()> may call <java.lang.Object: void <clinit>()>  
<Fish: void saySomething()> may call <java.lang.System: void <clinit>()>  
<Fish: void saySomething()> may call <java.io.PrintStream: void println(java.lang.String)>  
<Fish: void saySomething()> may call <java.lang.Object: void <clinit>()>  
Total Edges:16  
  
### PTA Output:  
Total Edges:9  
<Example: Animal selectAnimal()> may call <Cat: void <init>()>  
<Example: void main(java.lang.String[])> may call <java.lang.System: void <clinit>()>  
<Example: void main(java.lang.String[])> may call <Cat: void saySomething()>  
<Example: void main(java.lang.String[])> may call <java.lang.Object: void <clinit>()>  
<Example: void main(java.lang.String[])> may call <Example: Animal selectAnimal()>  
<Animal: void <init>()> may call <java.lang.Object: void <init>()>  
<Cat: void <init>()> may call <Animal: void <init>()>  
<Cat: void saySomething()> may call <java.lang.System: void <clinit>()>  
<Cat: void saySomething()> may call <java.lang.Object: void <clinit>()>  
  
### Conclusion:  
PTA is more precise than CHA.  
  
## Part 3 - Run TestSootLogging as an Application, once with "jimple" as an argument and once without (to generate Example.class file)
virtualinvoke $r2.<java.io.PrintStream: void println(java.lang.String)>("calling selectAnimal")
r1 = staticinvoke <Example: Animal selectAnimal()>()
virtualinvoke $r3.<java.io.PrintStream: void println(java.lang.String)>("calling saySomething")
virtualinvoke r1.<Animal: void saySomething()>()

### Run java Example in sootOutput  
calling println  
calling selectAnimal  
calling selectAnimal  
calling println  
calling saySomething  
calling saySomething  
purr

### Run TestSootLoggingHeap as an Application  
Thread Thread-6 wrote static field x  
Thread Thread-6 read static field y  
Thread Thread-6 read static field y  
Thread Thread-5 read static field y  
Thread Thread-5 wrote static field x  
Thread Thread-5 wrote static field out  
Thread Thread-5 wrote static field x
