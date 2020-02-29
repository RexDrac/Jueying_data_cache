imitation-weight: 0.5
replay-start-size: 10000
env-id: HumanoidBalanceFilter-v0
max-episode-num: 5000000
state-dim: 23
actor-lr: 0.0003
expert-num: 4
max-path-num: 20
critic-weight-decay: 1e-06
rollout-step-num: 1
normalized-action-bounds: [[0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]
 [0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0. 0.]]
test-num: 4
n-step: 1
max-step-num: 2500000000
task-weight: 0.5
dsr-gait-freq: 1.667
action-bounds: [[-0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981 -0.5236 -2.7925  0.6981
  -0.5236 -2.7925  0.6981]
 [ 0.5236  0.3491  2.7925  0.5236  0.3491  2.7925  0.5236  0.3491  2.7925
   0.5236  0.3491  2.7925]]
actor-output-bounds: [[-1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1. -1.]
 [ 1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.  1.]]
batch-size: 128
action-dim: 12
record-start-size: 10000.0
max-path-step: 5000
actor-logstd-bounds: [[-1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791
  -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791 -1.60943791]
 [-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
loss-output-bound-coeff: 0.0
actor-l2-reg: 0.0003
prioritized-exp-replay: True
actor-logstd-initial: [[-0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718
  -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718 -0.69314718]]
controlled-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
Physics-frequency: 1000
gating-activation-fn: ['relu', 'relu', 'None']
actor-weight-decay: 1e-06
LLC-frequency: 500
critic-l2-reg: 0.0003
loss-output-diff-coeff: 0
max-train-time: 10
expert-index: None
render-eval: False
gamma: 0.955
gating-index: None
categorical-distribution: {'v_max': 250, 'v_min': -10, 'n_atoms': 51}
max-test-time: 10
actor-action-joints: ['FR_hip_motor_2_chassis_joint', 'FR_upper_leg_2_hip_motor_joint', 'FR_lower_leg_2_upper_leg_joint', 'FL_hip_motor_2_chassis_joint', 'FL_upper_leg_2_hip_motor_joint', 'FL_lower_leg_2_upper_leg_joint', 'RR_hip_motor_2_chassis_joint', 'RR_upper_leg_2_hip_motor_joint', 'RR_lower_leg_2_upper_leg_joint', 'RL_hip_motor_2_chassis_joint', 'RL_upper_leg_2_hip_motor_joint', 'RL_lower_leg_2_upper_leg_joint']
dsr-gait-period: 0.6
squash-action: True
HLC-frequency: 25
tau: 0.001
replay-ratio: 1
epoch-num: 500
actor-layer-size: [256, 256]
epoch-step-num: 5000000
critic-layer-size: [256, 256]
loss-entropy-coeff: 0.0
critic-activation-fn: ['relu', 'relu', 'None']
gating-layer-size: [32, 32]
joint-interpolation: True
replay-buffer-size: 1000000
loss-output-smooth-coeff: 2.0
filter-action: True
reward-scale: 0.1
filter-torque: False
train-step-num: 1
critic-lr: 0.0003
total-step-num: 2500000000
interpolation: False
actor-activation-fn: ['relu', 'relu', 'None']
bullet-default-PD: False
