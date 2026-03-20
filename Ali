import { Link } from "react-router-dom";
import { motion } from "framer-motion";
import {
  Phone, CalendarCheck, MessageSquare, Clock, Users, Globe, Mic, ArrowRight,
  Zap, Route, UserPlus, Bell, Bot, BrainCircuit, Headphones, Languages,
  BookOpen, Repeat, Scissors, Heart, Stethoscope, SmilePlus, Hammer,
  Building2, Scale, Wrench, Star, ChevronRight
} from "lucide-react";
import { Button } from "@/components/ui/button";
import ScrollReveal from "@/components/ScrollReveal";
import SectionHeading from "@/components/SectionHeading";
import Navbar from "@/components/Navbar";
import Footer from "@/components/Footer";

const Hero = () => (
  <section className="relative overflow-hidden pt-32 pb-20 md:pt-40 md:pb-32">
    {/* Background effects */}
    <div className="pointer-events-none absolute inset-0">
      <div className="absolute left-1/2 top-0 h-[600px] w-[800px] -translate-x-1/2 -translate-y-1/2 rounded-full bg-primary/8 blur-[120px]" />
      <div className="absolute right-0 top-1/3 h-[400px] w-[400px] rounded-full bg-primary/5 blur-[100px]" />
    </div>

    <div className="container relative mx-auto px-4 lg:px-8">
      <div className="mx-auto max-w-4xl text-center">
        <motion.div
          initial={{ opacity: 0, y: 20, filter: "blur(6px)" }}
          animate={{ opacity: 1, y: 0, filter: "blur(0px)" }}
          transition={{ duration: 0.7, ease: [0.16, 1, 0.3, 1] }}
        >
          <span className="mb-6 inline-flex items-center gap-2 rounded-full border border-primary/30 bg-primary/10 px-4 py-1.5 text-xs font-medium text-primary">
            <Bot className="h-3.5 w-3.5" /> AI-Powered Receptionist Service
          </span>
        </motion.div>

        <motion.h1
          className="font-display text-4xl font-bold tracking-tight md:text-6xl lg:text-7xl"
          style={{ lineHeight: "1.05" }}
          initial={{ opacity: 0, y: 24, filter: "blur(6px)" }}
          animate={{ opacity: 1, y: 0, filter: "blur(0px)" }}
          transition={{ duration: 0.7, delay: 0.1, ease: [0.16, 1, 0.3, 1] }}
        >
          Never Miss a Call{" "}
          <span className="gradient-text">Again</span>
        </motion.h1>

        <motion.p
          className="mx-auto mt-6 max-w-2xl text-lg leading-relaxed text-muted-foreground md:text-xl"
          initial={{ opacity: 0, y: 20, filter: "blur(4px)" }}
          animate={{ opacity: 1, y: 0, filter: "blur(0px)" }}
          transition={{ duration: 0.6, delay: 0.25, ease: [0.16, 1, 0.3, 1] }}
        >
          Our AI receptionist answers calls, books appointments, responds naturally, and helps your business stay available — even when you're busy.
        </motion.p>

        <motion.div
          className="mt-10 flex flex-col items-center justify-center gap-4 sm:flex-row"
          initial={{ opacity: 0, y: 16 }}
          animate={{ opacity: 1, y: 0 }}
          transition={{ duration: 0.6, delay: 0.4, ease: [0.16, 1, 0.3, 1] }}
        >
          <Link to="/book">
            <Button size="lg" className="h-12 gap-2 bg-primary px-8 text-primary-foreground hover:bg-primary/90 active:scale-[0.97] transition-all text-base">
              Book an Appointment <ArrowRight className="h-4 w-4" />
            </Button>
          </Link>
          <Link to="/pricing">
            <Button size="lg" variant="outline" className="h-12 px-8 border-border/60 text-foreground hover:bg-secondary active:scale-[0.97] transition-all text-base">
              View Pricing
            </Button>
          </Link>
        </motion.div>
      </div>
    </div>
  </section>
);

const whatItDoes = [
  { icon: Clock, title: "Answers incoming calls 24/7" },
  { icon: Mic, title: "Speaks with a natural human-like voice" },
  { icon: CalendarCheck, title: "Books appointments directly into your calendar" },
  { icon: Repeat, title: "Handles cancellations and rescheduling" },
  { icon: MessageSquare, title: "Sends SMS confirmations and reminders" },
  { icon: UserPlus, title: "Captures new leads automatically" },
  { icon: BrainCircuit, title: "Answers common business questions" },
  { icon: Route, title: "Routes urgent calls when needed" },
];

const WhatItDoes = () => (
  <section className="py-24">
    <div className="container mx-auto px-4 lg:px-8">
      <SectionHeading
        label="How It Helps"
        title="What the AI Receptionist Does"
        description="A smart assistant that handles calls, bookings, and customer inquiries — so you don't have to."
      />
      <div className="mx-auto grid max-w-5xl gap-4 md:grid-cols-2">
        {whatItDoes.map((item, i) => (
          <ScrollReveal key={item.title} delay={i * 0.07}>
            <div className="flex items-center gap-4 rounded-xl border border-border/50 bg-card/50 p-5 card-hover">
              <div className="flex h-10 w-10 shrink-0 items-center justify-center rounded-lg bg-primary/10">
                <item.icon className="h-5 w-5 text-primary" />
              </div>
              <span className="text-sm font-medium">{item.title}</span>
            </div>
          </ScrollReveal>
        ))}
      </div>
    </div>
  </section>
);

const whyNeeded = [
  "Missed calls mean lost revenue",
  "Staff can't always answer the phone",
  "Customers want quick responses",
  "The AI handles repetitive tasks instantly",
  "Businesses save time and look more professional",
];

const WhyBusinessesNeedIt = () => (
  <section className="py-24">
    <div className="container mx-auto px-4 lg:px-8">
      <div className="mx-auto grid max-w-5xl items-center gap-16 lg:grid-cols-2">
        <ScrollReveal direction="left">
          <span className="mb-4 inline-block rounded-full border border-primary/30 bg-primary/10 px-4 py-1.5 text-xs font-medium uppercase tracking-wider text-primary">
            The Problem
          </span>
          <h2 className="font-display text-3xl font-bold tracking-tight md:text-4xl" style={{ lineHeight: "1.1" }}>
            Why Businesses <span className="gradient-text">Need It</span>
          </h2>
          <p className="mt-4 text-muted-foreground leading-relaxed">
            Every unanswered call is a missed opportunity. Your AI receptionist ensures no lead slips through the cracks.
          </p>
        </ScrollReveal>
        <div className="space-y-3">
          {whyNeeded.map((item, i) => (
            <ScrollReveal key={item} delay={i * 0.08} direction="right">
              <div className="flex items-center gap-3 rounded-xl border border-border/50 bg-card/50 p-4">
                <div className="flex h-8 w-8 shrink-0 items-center justify-center rounded-full bg-primary/10">
                  <ChevronRight className="h-4 w-4 text-primary" />
                </div>
                <span className="text-sm font-medium">{item}</span>
              </div>
            </ScrollReveal>
          ))}
        </div>
      </div>
    </div>
  </section>
);

const features = [
  { icon: Mic, title: "Natural Human Voice", desc: "Lifelike conversations that feel personal" },
  { icon: CalendarCheck, title: "Appointment Booking", desc: "Books directly into your calendar" },
  { icon: Zap, title: "Calendar Integration", desc: "Syncs with Google, Outlook & more" },
  { icon: MessageSquare, title: "SMS Confirmations", desc: "Automated text reminders & confirmations" },
  { icon: Route, title: "Call Routing", desc: "Routes urgent calls to the right person" },
  { icon: UserPlus, title: "Lead Capture", desc: "Never lose a potential customer" },
  { icon: Clock, title: "24/7 Availability", desc: "Always on, even after hours" },
  { icon: Languages, title: "Multi-Language", desc: "Communicates in multiple languages" },
  { icon: BookOpen, title: "Custom Knowledge", desc: "Trained on your business info" },
  { icon: Bell, title: "Follow-Up Automation", desc: "Automated follow-up workflows" },
];

const Features = () => (
  <section className="py-24 bg-card/30">
    <div className="container mx-auto px-4 lg:px-8">
      <SectionHeading
        label="Features"
        title="Everything Your Front Desk Needs"
        description="Powerful capabilities designed to keep your business running smoothly around the clock."
      />
      <div className="mx-auto grid max-w-6xl gap-5 sm:grid-cols-2 lg:grid-cols-3 xl:grid-cols-5">
        {features.map((f, i) => (
          <ScrollReveal key={f.title} delay={i * 0.05}>
            <div className="group rounded-xl border border-border/50 bg-card/80 p-6 text-center card-hover gradient-border">
              <div className="mx-auto mb-4 flex h-12 w-12 items-center justify-center rounded-xl bg-primary/10 transition-colors group-hover:bg-primary/20">
                <f.icon className="h-5 w-5 text-primary" />
              </div>
              <h3 className="font-display text-sm font-semibold">{f.title}</h3>
              <p className="mt-1.5 text-xs text-muted-foreground leading-relaxed">{f.desc}</p>
            </div>
          </ScrollReveal>
        ))}
      </div>
    </div>
  </section>
);

const steps = [
  { num: "01", title: "We Set Up Your AI Receptionist", desc: "Quick onboarding tailored to your business needs." },
  { num: "02", title: "We Customize It for You", desc: "Trained on your services, hours, and FAQs." },
  { num: "03", title: "It Answers Calls & Books Appointments", desc: "Handles inbound calls with natural conversation." },
  { num: "04", title: "You Save Time & Never Miss Opportunities", desc: "Focus on your business while AI handles the rest." },
];

const HowItWorks = () => (
  <section className="py-24">
    <div className="container mx-auto px-4 lg:px-8">
      <SectionHeading label="Process" title="How It Works" description="Getting started is simple. We handle the setup so you can focus on your business." />
      <div className="mx-auto grid max-w-5xl gap-6 md:grid-cols-2 lg:grid-cols-4">
        {steps.map((s, i) => (
          <ScrollReveal key={s.num} delay={i * 0.1}>
            <div className="relative rounded-xl border border-border/50 bg-card/50 p-6 card-hover">
              <span className="font-display text-3xl font-bold text-primary/20">{s.num}</span>
              <h3 className="mt-3 font-display text-base font-semibold">{s.title}</h3>
              <p className="mt-2 text-sm text-muted-foreground leading-relaxed">{s.desc}</p>
            </div>
          </ScrollReveal>
        ))}
      </div>
    </div>
  </section>
);

const industries = [
  { icon: Scissors, name: "Salons" },
  { icon: Heart, name: "Med Spas" },
  { icon: Stethoscope, name: "Clinics" },
  { icon: SmilePlus, name: "Dental Offices" },
  { icon: Hammer, name: "Contractors" },
  { icon: Building2, name: "Real Estate Teams" },
  { icon: Scale, name: "Law Firms" },
  { icon: Wrench, name: "Home Service Businesses" },
];

const Industries = () => (
  <section className="py-24 bg-card/30">
    <div className="container mx-auto px-4 lg:px-8">
      <SectionHeading label="Industries" title="Built for Service-Based Businesses" description="From salons to law firms, our AI receptionist adapts to your industry." />
      <div className="mx-auto grid max-w-4xl grid-cols-2 gap-4 sm:grid-cols-4">
        {industries.map((ind, i) => (
          <ScrollReveal key={ind.name} delay={i * 0.06}>
            <div className="flex flex-col items-center gap-3 rounded-xl border border-border/50 bg-card/50 p-6 text-center card-hover">
              <div className="flex h-12 w-12 items-center justify-center rounded-xl bg-primary/10">
                <ind.icon className="h-5 w-5 text-primary" />
              </div>
              <span className="text-sm font-medium">{ind.name}</span>
            </div>
          </ScrollReveal>
        ))}
      </div>
    </div>
  </section>
);

const testimonials = [
  { name: "Sarah Mitchell", role: "Owner, Glow Beauty Spa", text: "Since switching to the AI receptionist, we haven't missed a single booking. It pays for itself every month." },
  { name: "Dr. James Hartley", role: "Hartley Dental Clinic", text: "Our front desk was overwhelmed. Now the AI handles after-hours calls, cancellations, and rebookings seamlessly." },
  { name: "Marco Ribeiro", role: "MR Contracting", text: "I used to lose leads while on job sites. Now every call gets answered and I get a text with the details. Game changer." },
];

const Testimonials = () => (
  <section className="py-24">
    <div className="container mx-auto px-4 lg:px-8">
      <SectionHeading label="Testimonials" title="Trusted by Canadian Businesses" />
      <div className="mx-auto grid max-w-5xl gap-6 md:grid-cols-3">
        {testimonials.map((t, i) => (
          <ScrollReveal key={t.name} delay={i * 0.1}>
            <div className="flex h-full flex-col rounded-xl border border-border/50 bg-card/50 p-6 card-hover gradient-border">
              <div className="mb-4 flex gap-1">
                {[...Array(5)].map((_, j) => (
                  <Star key={j} className="h-4 w-4 fill-primary text-primary" />
                ))}
              </div>
              <p className="flex-1 text-sm leading-relaxed text-muted-foreground">"{t.text}"</p>
              <div className="mt-5 border-t border-border/50 pt-4">
                <p className="text-sm font-semibold">{t.name}</p>
                <p className="text-xs text-muted-foreground">{t.role}</p>
              </div>
            </div>
          </ScrollReveal>
        ))}
      </div>
    </div>
  </section>
);

const FinalCTA = () => (
  <section className="py-24">
    <div className="container mx-auto px-4 lg:px-8">
      <ScrollReveal>
        <div className="relative mx-auto max-w-4xl overflow-hidden rounded-2xl border border-primary/20 bg-card p-12 text-center md:p-16">
          <div className="pointer-events-none absolute inset-0">
            <div className="absolute left-1/2 top-1/2 h-[400px] w-[600px] -translate-x-1/2 -translate-y-1/2 rounded-full bg-primary/8 blur-[100px]" />
          </div>
          <div className="relative">
            <h2 className="font-display text-3xl font-bold tracking-tight md:text-4xl" style={{ lineHeight: "1.1" }}>
              Ready to <span className="gradient-text">Automate</span> Your Front Desk?
            </h2>
            <p className="mx-auto mt-4 max-w-lg text-muted-foreground leading-relaxed">
              Book a free consultation and discover how an AI receptionist can save you time, capture more leads, and transform your business.
            </p>
            <div className="mt-8 flex flex-col items-center justify-center gap-4 sm:flex-row">
              <Link to="/book">
                <Button size="lg" className="h-12 gap-2 bg-primary px-8 text-primary-foreground hover:bg-primary/90 active:scale-[0.97] transition-all">
                  Book a Free Consultation <ArrowRight className="h-4 w-4" />
                </Button>
              </Link>
              <Link to="/contact">
                <Button size="lg" variant="outline" className="h-12 px-8 border-border/60 hover:bg-secondary active:scale-[0.97] transition-all">
                  Contact Us
                </Button>
              </Link>
            </div>
          </div>
        </div>
      </ScrollReveal>
    </div>
  </section>
);

const Index = () => (
  <div className="min-h-screen">
    <Navbar />
    <Hero />
    <WhatItDoes />
    <WhyBusinessesNeedIt />
    <Features />
    <HowItWorks />
    <Industries />
    <Testimonials />
    <FinalCTA />
    <Footer />
  </div>
);

export default Index;
