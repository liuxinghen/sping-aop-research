# sping-aop-research

## Notes

1. spring framework use proxy-based aop (interface-proxied JDK-based vs target-class-proxied CGLIB-based)
2. spring framework use run-time weaving by default
3. AspectJ is independent to Spring framework
4. AspectJ supports Load-time weaving (LTW) and Compile-time weaving (CTW)
5. for spring context, xml-based configuration has different class loading order with @Configuration-based config
