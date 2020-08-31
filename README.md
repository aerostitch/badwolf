我是光年实验室高级招聘经理。
我在github上访问了你的开源项目，你的代码超赞。你最近有没有在看工作机会，我们在招软件开发工程师，拉钩和BOSS等招聘网站也发布了相关岗位，有公司和职位的详细信息。
我们公司在杭州，业务主要做流量增长，是很多大型互联网公司的流量顾问。公司弹性工作制，福利齐全，发展潜力大，良好的办公环境和学习氛围。
公司官网是http://www.gnlab.com,公司地址是杭州市西湖区古墩路紫金广场B座，若你感兴趣，欢迎与我联系，
电话是0571-88839161，手机号：18668131388，微信号：echo 'bGhsaGxoMTEyNAo='|base64 -D ,静待佳音。如有打扰，还请见谅，祝生活愉快工作顺利。

# BadWolf

[![Test Status](https://github.com/google/badwolf/workflows/tests/badge.svg)](https://github.com/google/badwolf/actions?query=workflow%3Atests)
[![Go Report Card](https://goreportcard.com/badge/github.com/google/badwolf)](https://goreportcard.com/report/github.com/google/badwolf)
[![GoDoc](https://godoc.org/github.com/google/badwolf?status.svg)](https://godoc.org/github.com/google/badwolf)

BadWolf is a temporal graph store loosely modeled after the concepts introduced
by the
[Resource Description Framework (RDF)](https://en.wikipedia.org/wiki/Resource_Description_Framework).
It presents a flexible storage abstraction, efficient query language, and
data-interchange model for representing a directed graph that accommodates the
storage and linking of arbitrary objects without the need for a rigid schema.

BadWolf began as a [triplestore](https://en.wikipedia.org/wiki/Triplestore),
but triples have been expanded to quads to allow simpler and flexible temporal
reasoning. Because BadWolf is designed for generalized relationship storage,
most of the web-related idiosyncrasies of RDF are not used and have been toned
down or directly removed and focuses on its time reasoning aspects.

In case you are curious about the name, BadWolf is named after the
[BadWolf entity](http://tardis.wikia.com/wiki/Bad_Wolf_(entity) ) as it appeared
in Dr. Who series episode _"The Parting Of Ways"_ after Rose Tyler looked into
the Time Vortex itself. The BadWolf entity scattered events in time as self
encode messages, creating a looped ontological paradox. Hence, naming a temporal
graph store after the entity seemed appropriate.

You can find more detail information on each of the components of BadWolf below:

* [Data Abstractions for Temporal Graph Modeling](./docs/temporal_graph_modeling.md).
* [Storage Abstraction Layer](./docs/storage_abstraction_layer.md).
* [Graph Marshaling/Unmarshaling](./docs/graph_serialization.md).
* [BadWolf Query Language overview](./docs/bql.md).
* [BadWolf Query Language planner](./docs/bql_query_planner.md).
* [BadWolf Query Language practical examples](./docs/bql_practical_examples.md).
* [BadWolf command line tool](./docs/command_line_tool.md).

Please keep in mind that this project is under active development and there
will be no guarantees on API stability till the first stable 1.0 release.

You can reach us here or via
[@badwolf_project](https://twitter.com/badwolf_project) on Twitter.

For more information, presentation, or to find other related projects that
using BadWolf check the
[project website](http://google.github.io/badwolf/).
